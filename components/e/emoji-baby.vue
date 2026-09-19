<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="a-wcklbfj"/><path class="m413n1bnf"/><path class="knfp8wb8o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:emoji-baby" /></template>
<style>
.a-wcklbfj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M17.507 17.755s.722-.721 1.443-.721s1.443.72 1.443.72m7.214.001s.721-.721 1.443-.721s1.443.72 1.443.72m4.328.938c2.164 2.163 2.886 15.643 2.886 21.41v1.802m-27.414 0v-1.802c0-5.767.722-19.247 2.886-21.41m8.441 4.542c-.794-.217-1.227-.433-1.227-.433m7.214 0s-.36.216-1.082.433");
}

.knfp8wb8o {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M21.836 23.161a2.163 2.163 0 0 0 4.328 0h0a2.163 2.163 0 0 0-4.328 0M10.293 41.904c9.05.96 18.22.61 27.414 0");
}

.m413n1bnf {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M29.771 27.847c5.772-2.162 5.05-8.65 5.05-11.39C34.821 10.042 30.348 5.5 24 5.5s-10.821 4.542-10.821 10.957c0 2.74-.722 9.228 5.122 11.39c2.669 1.01 8.729.937 11.47 0M21.114 9.104l-.721.721M24 8.384l-.721 1.441m3.607-.721l.721.721");
}

</style>
