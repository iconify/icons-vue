<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="uzjl_hbdu"/><path class="j4jnpozkt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:contract-interaction" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.j4jnpozkt {
  d: path("M13.5 2.5v4h4M4 19h16M6.5 16.75L4 19l2.5 2.25m11-4.5L20 19l-2.5 2.25");
}

.uzjl_hbdu {
  d: path("M8.5 2.5h5l4 4v5a2 2 0 0 1-2 2h-7a2 2 0 0 1-2-2v-7a2 2 0 0 1 2-2");
}

</style>
