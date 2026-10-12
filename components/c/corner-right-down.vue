<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="bq82uemcg"/><path class="grlcs-vwr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:corner-right-down" /></template>
<style>
.bq82uemcg {
  d: path("M4.25 4.25h8a2.5 2.5 0 0 1 2.5 2.5v12.5");
}

.grlcs-vwr {
  d: path("m11 15.5l3.75 3.75l3.75-3.75");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
