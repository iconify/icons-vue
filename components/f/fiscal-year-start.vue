<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="apr_wd27w"/><path class="lfpehachd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:fiscal-year-start" /></template>
<style>
.apr_wd27w {
  d: path("M12.7 20.5H3.5V5h17v6.9M8 3v4m8-4v4M3.5 10h17m-5 11.5v-7");
}

.lfpehachd {
  d: path("M15.5 14.75H21l-1.5 2l1.5 2h-5.5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
