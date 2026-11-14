<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="krbz_kmgx"/><path class="qgpj5ee6g"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:gate-remote" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.krbz_kmgx {
  d: path("M7.875 9h.25a4.375 4.375 0 0 1 4.375 4.375v3.75A4.375 4.375 0 0 1 8.125 21.5h-.25A4.375 4.375 0 0 1 3.5 17.125v-3.75A4.375 4.375 0 0 1 7.875 9");
}

.qgpj5ee6g {
  d: path("M6.75 13.25a1.25 1.25 0 1 0 2.5 0a1.25 1.25 0 1 0-2.5 0m0 4.5a1.25 1.25 0 1 0 2.5 0a1.25 1.25 0 1 0-2.5 0m6.358-12.197a3.5 3.5 0 0 1 2.839 2.839m-2.318-5.793a6.5 6.5 0 0 1 5.272 5.272");
}

</style>
