<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="o9o4t05de"/><path class="ec-jcit8z"/><path class="ugs22v-bb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:course-outline-thin" /></template>
<style>
.ec-jcit8z {
  d: path("M5 10h14v4H5Z");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.o9o4t05de {
  d: path("M3 3h14v4H3Z");
}

.ugs22v-bb {
  d: path("M7 17h14v4H7Z");
}

</style>
