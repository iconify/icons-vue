<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aa4z-7c0k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:hand-wash" /></template>
<style>
.aa4z-7c0k {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 21.5h10c1.5 0 3-.5 4-1.5l3.75-3.75c.75-.75.5-2-.5-2.25c-.75-.25-1.5.25-2 .75L16.5 16.5H11M2.5 6h7C11 6 12 7 12 8.5v1M6.25 6V3.5m-2 0h4M12 12v1.5m-9 3h3");
}

</style>
