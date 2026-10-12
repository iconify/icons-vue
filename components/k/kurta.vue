<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="w6cfsfbbq"/><path class="pbapgub8u"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:kurta" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.pbapgub8u {
  d: path("M9.75 3L12 5.25L14.25 3M12 5.25v5");
}

.w6cfsfbbq {
  d: path("M9.75 2.75h4.5q.75 0 1.41.35l3.43 1.8q.66.35.87 1.07l1.08 3.81q.21.72-.46 1.06l-1.16.57q-.67.34-1.11-.27l-1.12-1.53q-.44-.61-.44.14V20.5q0 .75-.75.75H8q-.75 0-.75-.75V9.75q0-.75-.44-.14l-1.12 1.53q-.44.61-1.11.27l-1.16-.57q-.67-.34-.46-1.06l1.08-3.81q.21-.72.87-1.07l3.43-1.8q.66-.35 1.41-.35");
}

</style>
