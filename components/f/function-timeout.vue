<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="sdu05fs9z"/><path class="sbezkcbzn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:function-timeout" /></template>
<style>
.sbezkcbzn {
  d: path("M19.5 14.75v1l-3 4.5v1");
}

.sdu05fs9z {
  d: path("m6.5 3l-4 4.5l4 4.5m7-9.5l-3 10m7-9.5l4 4.5l-4 4.5m-2 2.75h5m-5 6.5h5m-4-6.5v1l3 4.5v1");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
