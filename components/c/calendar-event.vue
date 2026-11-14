<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="gkcrv-ahb"/><path class="zd4fkgk7p"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:calendar-event" /></template>
<style>
.gkcrv-ahb {
  d: path("M3 3.5h18v18H3ZM8 2v2.75M16 2v2.75M3 7.5h18");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.zd4fkgk7p {
  fill: currentColor;
  d: path("M12 10.25L13 13l3 .25L13.75 15l.75 3l-2.5-1.75L9.5 18l.75-3L8 13.25l3-.25Z");
}

</style>
