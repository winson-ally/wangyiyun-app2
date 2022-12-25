<template>
<div>
  <TopNav></TopNav>
  <SwiperTop></SwiperTop>
  <IconList></IconList>
  <MusicList></MusicList>
  </div>
</template>

<script lang="ts">
import { Options, Vue } from 'vue-class-component';
import TopNav from '@/components/home/TopNav.vue'
import SwiperTop from '@/components/home/SwiperTop.vue'
import IconList from '@/components/home/IconList.vue'
import MusicList from '@/components/home/MusicList.vue'
 // @ is an alias to /src

@Options({
  components: {
    TopNav,SwiperTop,IconList,MusicList
  },
})
export default class HomeView extends Vue {}
</script>


