<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cmpexgbfp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:dress" /></template>
<style>
.cmpexgbfp {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M7.5 10L6.0261 4.84C5.7319 3.81 6.3008 2.73 7.3167 2.39L8.5 2V2.5C8.5 4.43 10.067 6 12 6C13.933 6 15.5 4.43 15.5 2.5V2L16.6833 2.39C17.6992 2.73 18.2681 3.81 17.9739 4.84L16.5 10M7.5 10L4.1 19.37C3.6805 20.66 4.6322 22 5.9973 22H18.0027C19.3678 22 20.3195 20.66 19.9 19.37L16.5 10M7.5 10H16.5");
}

</style>
