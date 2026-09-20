<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="okud9xj_d"/><path class="up7bczw9b"/><path class="xrq8zbb_a"/><path class="j8fsnzfoe"/><path class="w8s_cgg4z"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:library-card-outline-thin" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.j8fsnzfoe {
  d: path("M13 10h6");
}

.okud9xj_d {
  d: path("M2 7a2 2 0 0 1 2 -2h16a2 2 0 0 1 2 2v10a2 2 0 0 1 -2 2H4a2 2 0 0 1 -2 -2Z");
}

.up7bczw9b {
  d: path("M4 11a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
}

.w8s_cgg4z {
  d: path("M13 14h4");
}

.xrq8zbb_a {
  d: path("M5 15h4");
}

</style>
