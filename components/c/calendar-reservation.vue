<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="pvh6wmb3m"/><path class="ewpkw_sfj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:calendar-reservation" /></template>
<style>
.ewpkw_sfj {
  d: path("M15.5 16a.5.5 0 1 0 1 0a.5.5 0 1 0-1 0Z");
}

.pvh6wmb3m {
  d: path("M3.5 5h17v15.5h-17ZM8 3v4m8-4v4M3.5 10h17m-11 3v6M8 13v2.5m3-2.5v2.5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
