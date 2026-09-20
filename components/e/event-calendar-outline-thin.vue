<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="mc1omvbiw"/><path class="c-hbuyb5n"/><path class="n-7t0yb1r"/><path class="n887hrq4r"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:event-calendar-outline-thin" /></template>
<style>
.c-hbuyb5n {
  d: path("M4 7c1.5 2 3.5 2 5 0 1.5 2 3.5 2 5 0 1.5 2 3.5 2 5 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.mc1omvbiw {
  d: path("M3 6a2 2 0 0 1 2 -2h14a2 2 0 0 1 2 2v13a2 2 0 0 1 -2 2H5a2 2 0 0 1 -2 -2Z");
}

.n-7t0yb1r {
  d: path("M3 13h18");
}

.n887hrq4r {
  d: path("M7 17h6");
}

</style>
