<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ii3rr8bvd"/><path class="qqz_pcblr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:bank-building" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ii3rr8bvd {
  d: path("M3.75 20.25v-11q0-1 .84-1.54l6.57-4.17q.84-.54 1.68 0l6.57 4.17q.84.54.84 1.54v11q0 1-1 1H4.75q-1 0-1-1");
}

.qqz_pcblr {
  d: path("M14 11c-.5-.75-1.25-1-2-1c-1.25 0-2.25.6-2.25 1.6c0 2.15 4.5 1.15 4.5 3.3c0 1-1 1.6-2.25 1.6c-.75 0-1.5-.25-2-1m2-6.75V10m0 6.5v1.25M6.75 11v6.5m10.5-6.5v6.5");
}

</style>
