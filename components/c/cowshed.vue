<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ey33_84de"/><path class="ztxfoznqy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:cowshed" /></template>
<style>
.ey33_84de {
  d: path("m3.316 9.485l7.75-4.895a1.75 1.75 0 0 1 1.868 0l7.75 4.895a1.75 1.75 0 0 1 .816 1.48v7.785a1.75 1.75 0 0 1-1.75 1.75H4.25a1.75 1.75 0 0 1-1.75-1.75v-7.785a1.75 1.75 0 0 1 .816-1.48");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ztxfoznqy {
  d: path("m10.5 16l-.5-3a.5.5 0 0 1 .5-.5h3a.5.5 0 0 1 .5.5l-.5 3m-2.625 0h2.25a1.375 1.375 0 0 1 1.375 1.375a1.375 1.375 0 0 1-1.375 1.375h-2.25A1.375 1.375 0 0 1 9.5 17.375A1.375 1.375 0 0 1 10.875 16M10 13.5c-.93.16-1.83-.06-2.25-.75c.65-.44 1.55-.44 2.25 0m4 .75c.93.16 1.82-.06 2.25-.75c-.65-.44-1.55-.44-2.25 0m-3-.25c-.12-.75-.35-1.2-1-1.5m3.25 1.5c-.12-.75.1-1.2.75-1.5");
}

</style>
