<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y6861xbof"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:chart-polar-scatter" /></template>
<style>
.y6861xbof {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M14.22 3.05h.01q.73.18 1.41.48h.01q.69.3 1.32.71h.01q.63.4 1.18.9l.01.01q.56.5 1.03 1.09t.84 1.24v.01q.37.65.62 1.35v.01q.26.7.4 1.44v.01q.14.73.16 1.48v.01q.01.75-.09 1.49v.01q-.11.74-.33 1.46q-.23.72-.56 1.39l-.01.01q-.33.67-.77 1.27l-.01.01q-.44.6-.92.03l-4.55-5.43q-.48-.58-.48-1.33l-.01-7.08q0-.75.73-.57m-.06 14.53zq-.44.17-.9.27q-.47.1-.94.12q-.47.03-.94-.02t-.93-.17q-.45-.12-.89-.32q-.43-.19-.82-.45q-.4-.26-.75-.57q-.35-.32-.65-.69t.41-.62l3.07-1.11q.71-.25 1.19.32l2.11 2.49q.48.58.04.75m-9.62-5.1zq-.04-.63.03-1.26q.06-.63.23-1.24q.17-.6.44-1.18q.28-.57.64-1.09q.36-.51.81-.96q.44-.45.95-.82q.52-.37 1.09-.65t1.17-.45q.61-.18.61.57l-.01 4.8q0 .75-.7 1.01l-4.51 1.65q-.71.25-.75-.38");
}

</style>
