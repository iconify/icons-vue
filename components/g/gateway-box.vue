<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pzldsibxd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:gateway-box" /></template>
<style>
.pzldsibxd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12.5 16.5h-10V7H20v5.6M6 7V2.5M16.5 7V2.5m-10 9.25h.01M15 18l3.5-3l3.5 3v3.5h-7Z");
}

</style>
