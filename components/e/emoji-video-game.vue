<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="fhkwzabvm"/><path class="pwwm56cdd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:emoji-video-game" /></template>
<style>
.fhkwzabvm {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24.027 28.726H17.75c-.407 0-.772.232-.967.59c-2.078 3.81-4.858 4.71-5.613 4.853a2 2 0 0 1-.292.037c-8.655.255-4.264-11.153-4.264-11.153c1.252-3.659 4.275-7.955 5.293-8.946c.21-.204.487-.317.779-.317h22.628c.293 0 .57.113.78.317c1.017.991 4.04 5.287 5.292 8.946c0 0 4.391 11.409-4.264 11.153a2 2 0 0 1-.292-.037c-.755-.142-3.534-1.043-5.613-4.854a1.11 1.11 0 0 0-.967-.59h-6.277");
}

.pwwm56cdd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M18.141 24a2.403 2.403 0 0 0 4.807 0h0a2.403 2.403 0 0 0-4.807 0m6.911 0a2.403 2.403 0 0 0 4.807 0h0a2.403 2.403 0 0 0-4.807 0m5.565-4.337a.961.961 0 0 0 1.923.002v-.002a.961.961 0 0 0-1.923-.002zm5.089 0a.961.961 0 0 0 1.923 0v0a.961.961 0 0 0-1.923-.001zm-2.544 2.256a.961.961 0 0 0 1.923 0v0a.961.961 0 0 0-1.923-.001zm0-4.487a.961.961 0 0 0 1.923 0v0a.961.961 0 0 0-1.923-.001zm-19.18-.582v5.625m-2.812-2.793h5.626");
}

</style>
