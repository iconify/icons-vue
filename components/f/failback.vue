<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="pn8q78wmg"/><path class="o8cqgnbov"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:failback" /></template>
<style>
.o8cqgnbov {
  d: path("m17.5 15.5l-2 2l2 2");
}

.pn8q78wmg {
  d: path("M3 2.5h16v6H3Zm8.8 14.75H3v-6h16v1.8M6.5 5.5h.01m-.01 8.75h.01m8.99 3.25h4a2 2 0 0 1 0 4h-3");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
