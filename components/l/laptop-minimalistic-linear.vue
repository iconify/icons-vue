<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="zc2mgbctw"/><path class="mbp_w6jfq"/><path class="im1hkobej"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:laptop-minimalistic-linear" /></template>
<style>
.im1hkobej {
  d: path("M15 15H9");
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.mbp_w6jfq {
  d: path("M22 21H2");
}

.zc2mgbctw {
  d: path("M7 18H17C18.8856 18 19.8284 18 20.4142 17.4142C21 16.8284 21 15.8856 21 14V9C21 6.17157 21 4.75736 20.1213 3.87868C19.2426 3 17.8284 3 15 3H9C6.17157 3 4.75736 3 3.87868 3.87868C3 4.75736 3 6.17157 3 9V14C3 15.8856 3 16.8284 3.58579 17.4142C4.17157 18 5.11438 18 7 18Z");
}

</style>
