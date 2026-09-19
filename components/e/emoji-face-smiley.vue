<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="vy8f_hbwd"/><path class="gcw30fb6o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:emoji-face-smiley" /></template>
<style>
.gcw30fb6o {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M35.744 23.975s-4.746 3.813-11.718 3.813c-6.943 0-11.77-3.814-11.77-3.814c0 6.51 5.26 11.77 11.77 11.77c6.484 0 11.717-5.26 11.717-11.77");
}

.vy8f_hbwd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M30.194 15.152v4.826m-12.307-4.826v4.826M24.04 42.5c10.215 0 18.46-8.285 18.46-18.54c0-10.215-8.245-18.46-18.46-18.46C13.785 5.5 5.5 13.745 5.5 23.96c0 10.255 8.285 18.54 18.54 18.54");
}

</style>
