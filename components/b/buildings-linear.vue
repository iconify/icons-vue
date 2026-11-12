<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="xpzbxokqs"/><path class="pbjx0cciw"/><path class="uwhiofy0j"/><path class="ei794fi6p"/><path class="ts5ptqk6t"/><path class="gg36kokbr"/><path class="sjohn6bax"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:buildings-linear" /></template>
<style>
.ei794fi6p {
  d: path("M9 22V19");
}

.gg36kokbr {
  d: path("M6 11H12");
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.pbjx0cciw {
  d: path("M21 22V6C21 4.11438 21 3.17157 20.4143 2.58579C19.8285 2 18.8857 2 17 2H15C13.1144 2 12.1716 2 11.5858 2.58579C11.1143 3.05733 11.0223 3.76022 11.0044 5");
}

.sjohn6bax {
  d: path("M6 14H12");
}

.ts5ptqk6t {
  d: path("M6 8H12");
}

.uwhiofy0j {
  d: path("M15 22V9C15 7.11438 15 6.17157 14.4142 5.58579C13.8284 5 12.8856 5 11 5H7C5.11438 5 4.17157 5 3.58579 5.58579C3 6.17157 3 7.11438 3 9V22");
}

.xpzbxokqs {
  d: path("M22 22L2 22");
}

</style>
