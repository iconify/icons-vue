<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="bpciasb2z"/><path class="c11_n0b6s"/><path class="k3juqlbuw"/><path class="kq98nmbqp"/><path class="p5fzfqbvy"/><path class="y4a8ig_7t"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:bundle-save-outline-thin" /></template>
<style>
.bpciasb2z {
  d: path("M3 5.5a2 2 0 0 1 2 -2h14a2 2 0 0 1 2 2v10a2 2 0 0 1 -2 2H5a2 2 0 0 1 -2 -2Z");
}

.c11_n0b6s {
  d: path("M6.5 19.5a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.k3juqlbuw {
  d: path("M15.5 19.5a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.kq98nmbqp {
  d: path("M8.5 8a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.p5fzfqbvy {
  d: path("m9 13 6 -6");
}

.y4a8ig_7t {
  d: path("M13.5 12a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

</style>
