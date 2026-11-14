<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="gtip9tb_y"/><path class="vxhs26bqx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:leaf-bag" /></template>
<style>
.gtip9tb_y {
  d: path("M5 8h14l1 13H4Zm4 0V6.5a3 3 0 0 1 6 0V8");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.vxhs26bqx {
  d: path("M8.75 17.75c0-4.25 2.5-6.75 6.5-6.75c0 4.25-2.5 6.75-6.5 6.75Z");
}

</style>
