<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="izzh0hbmc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:flow-off-page-duotone" /></template>
<style>
.izzh0hbmc {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M5 5L19 5C20.6569 5 22 6.3431 22 8L22 11C22 11.6295 21.7036 12.2223 21.2 12.6L13.2 18.6C12.4889 19.1333 11.5111 19.1333 10.8 18.6L2.8 12.6C2.2964 12.2223 2 11.6295 2 11L2 8C2 6.3431 3.3431 5 5 5Z");
}

</style>
