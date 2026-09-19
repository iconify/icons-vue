<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="mqjauu0cl"/><path class="r_tvfg-_m"/><path class="x-4v47rve"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:breeno" /></template>
<style>
.mqjauu0cl {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M45.5 24c0 11.874-9.626 21.5-21.5 21.5h0C12.126 45.5 2.5 35.874 2.5 24h0C2.5 12.126 12.126 2.5 24 2.5h0c11.874 0 21.5 9.626 21.5 21.5");
}

.r_tvfg-_m {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M37.692 24c-2.437 7.562-10.542 13.692-18.104 13.692S7.872 31.562 10.308 24q0 0 0 0c2.437-7.562 10.542-13.691 18.103-13.691s11.717 6.13 9.28 13.691");
}

.x-4v47rve {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M34.723 26.24c4.191 7.054 2.788 11.77-3.135 10.532c-5.922-1.237-14.12-7.958-18.311-15.012s-2.788-11.77 3.135-10.532c5.922 1.237 14.12 7.958 18.311 15.012");
}

</style>
