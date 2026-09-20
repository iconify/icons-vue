<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="iaozfqbuj"/><path class="l01wrb87q"/><path class="hf8zy6boi"/><path class="n58clabmo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:database-search-outline-bold" /></template>
<style>
.hf8zy6boi {
  d: path("M8.5 15.5a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
}

.iaozfqbuj {
  d: path("M14.5 4H17a3 3 0 0 1 3 3v10a3 3 0 0 1 -3 3H7a3 3 0 0 1 -3 -3V8l4 -4h2.5");
}

.l01wrb87q {
  d: path("M7 10.5h10");
}

.n58clabmo {
  d: path("M13.5 17.5 16 20");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

</style>
