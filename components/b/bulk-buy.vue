<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i0rjpd2vg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:bulk-buy" /></template>
<style>
.i0rjpd2vg {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.75 2.75h6.75v6.5H3.75Zm9.5 0H20v6.5h-6.75ZM3.75 12h6.75v6.5H3.75Zm9.5 0H20v6.5h-6.75ZM2.5 18.5h19M5 18.5v3m14-3v3");
}

</style>
