<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="mj6t7h_3b"/><path class="oa_syzmnz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:code-terminal" /></template>
<style>
.mj6t7h_3b {
  d: path("M2.5 4h19v16h-19Zm0 4.5h19");
}

.oa_syzmnz {
  d: path("M6.5 11.5L9 14l-2.5 2.5m5 0H17");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
