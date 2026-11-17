<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v042v4nwa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:car-electric" /></template>
<style>
.v042v4nwa {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M5.3518 9L5 10.1707C3.8348 10.5825 3 11.6937 3 13V18.0346C3 19.12 3.88 20 4.9654 20C5.8673 20 6.6535 19.3862 6.8722 18.5113L7 18H17L17.1278 18.5113C17.3465 19.3862 18.1327 20 19.0346 20C20.12 20 21 19.12 21 18.0346V13C21 11.6937 20.1652 10.5825 19 10.1707L18.6482 9M5.3518 9L6.7199 5.8157C7.1932 4.714 8.2771 4 9.4762 4H14.5238C15.7229 4 16.8068 4.714 17.2801 5.8157L18.6482 9M5.3518 9H3.5M18.6482 9H20.5M13 8L10 11H14L11 14");
}

</style>
