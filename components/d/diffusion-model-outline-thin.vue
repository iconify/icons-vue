<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="iaozfqbuj"/><path class="c4o3x9bhp"/><path class="chgl46v6k"/><path class="i3rtqmu1v"/><path class="vny6l674c"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:diffusion-model-outline-thin" /></template>
<style>
.c4o3x9bhp {
  d: path("M8 9a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.chgl46v6k {
  d: path("M13.5 8.5a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.i3rtqmu1v {
  d: path("M9 15.5a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.iaozfqbuj {
  d: path("M14.5 4H17a3 3 0 0 1 3 3v10a3 3 0 0 1 -3 3H7a3 3 0 0 1 -3 -3V8l4 -4h2.5");
}

.vny6l674c {
  d: path("M14.5 14.5a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

</style>
