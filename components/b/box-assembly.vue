<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="rrx4-qqxm"/><path class="af4mucqbz"/><path class="r2pk93brh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:box-assembly" /></template>
<style>
.af4mucqbz {
  d: path("m4 10l8-3.5l8 3.5l-8 3.5Zm8 3.5v7");
}

.r2pk93brh {
  d: path("M4 10L2.5 6.5l8-3.5L12 6.5m0 0L13.5 3l8 3.5L20 10");
}

.rrx4-qqxm {
  d: path("M4 10v7l8 3.5l8-3.5v-7");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
