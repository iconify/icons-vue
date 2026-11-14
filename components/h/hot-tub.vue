<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="bql_x2b5m"/><path class="pso4sy5ql"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:hot-tub" /></template>
<style>
.bql_x2b5m {
  d: path("M3 11a9 2 0 1 0 18 0a9 2 0 1 0-18 0Z");
}

.pso4sy5ql {
  d: path("M3 11v8a9 2.5 0 0 0 18 0v-8M7.5 12.75v8.5M12 13v8.5m4.5-8.75v8.5M8 7.5c-.75-.75-.75-1.75 0-2.5s.75-1.75 0-2.5m4 5c-.75-.75-.75-1.75 0-2.5s.75-1.75 0-2.5m4 5c-.75-.75-.75-1.75 0-2.5s.75-1.75 0-2.5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
