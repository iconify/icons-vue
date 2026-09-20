<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="q737qqeus"/><path class="hkrm8eiuq"/><path class="aq5i5tblx"/><path class="l4egjkszt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:lawnmower-outline-thin" /></template>
<style>
.aq5i5tblx {
  d: path("M4 17a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.hkrm8eiuq {
  d: path("m16 13 5 -5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.l4egjkszt {
  d: path("M12 17a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.q737qqeus {
  d: path("M4 11v4h12v-4Z");
}

</style>
