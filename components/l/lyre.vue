<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vby1b5y-a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:lyre" /></template>
<style>
.vby1b5y-a {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8 20.25c-3-1-3.75-4.25-3.75-7.75V7.25C4.25 5.5 3.75 4 3 2.75m13 17.5c3-1 3.75-4.25 3.75-7.75V7.25c0-1.75.5-3.25 1.25-4.5M4.25 7.25h15.5M8 20.25h8m-7-13v13m3-13v13m3-13v13");
}

</style>
