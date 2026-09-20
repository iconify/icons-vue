<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="d251mrbie"/><path class="ukjt4fb6s"/><path class="o035hszqc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:event-driven-outline-thin" /></template>
<style>
.d251mrbie {
  d: path("m16 3 -5 5h3l-5 5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.o035hszqc {
  d: path("m14 14 3 3 -3 3");
}

.ukjt4fb6s {
  d: path("M3 17h12");
}

</style>
