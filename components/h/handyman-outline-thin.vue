<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="k74vnib1e"/><path class="fqjewfbna"/><path class="bkx9mvb8q"/><path class="c744qo9dt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:handyman-outline-thin" /></template>
<style>
.bkx9mvb8q {
  d: path("M14 20v-7h8v7Z");
}

.c744qo9dt {
  d: path("M16 13v-3h4v3");
}

.fqjewfbna {
  d: path("M2 16a4 4 0 0 1 8 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.k74vnib1e {
  d: path("M3 7a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
}

</style>
