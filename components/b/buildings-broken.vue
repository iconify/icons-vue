<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="xpzbxokqs"/><path class="solvq69mi"/><path class="ek9va93-s"/><path class="ei794fi6p"/><path class="ts5ptqk6t"/><path class="hmsbl8qws"/><path class="sjohn6bax"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:buildings-broken" /></template>
<style>
.ei794fi6p {
  d: path("M9 22V19");
}

.ek9va93-s {
  d: path("M3 9C3 7.11438 3 6.17157 3.58579 5.58579C4.17157 5 5.11438 5 7 5H11C12.8856 5 13.8284 5 14.4142 5.58579C15 6.17157 15 7.11438 15 9V12M3 22V13M15 16V22");
}

.hmsbl8qws {
  d: path("M6 11H7M9.5 11H12");
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.sjohn6bax {
  d: path("M6 14H12");
}

.solvq69mi {
  d: path("M11.0044 5C11.0223 3.76022 11.1143 3.05733 11.5858 2.58579C12.1716 2 13.1144 2 15 2H17C18.8857 2 19.8285 2 20.4143 2.58579C21 3.17157 21 4.11438 21 6V9M21 13V22");
}

.ts5ptqk6t {
  d: path("M6 8H12");
}

.xpzbxokqs {
  d: path("M22 22L2 22");
}

</style>
