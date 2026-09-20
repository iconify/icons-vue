<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="ux97gqb3r"/><path class="n6ndjw6jf"/><path class="v8c0ocbfs"/><path class="c27cgq4un"/><path class="jlfl_ccwj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:chunk-add-outline-regular" /></template>
<style>
.c27cgq4un {
  d: path("M18 8v8");
}

.jlfl_ccwj {
  d: path("M14 12h8");
}

.n6ndjw6jf {
  d: path("M4 9h7");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.ux97gqb3r {
  d: path("M2 6a2 2 0 0 1 2 -2h7a2 2 0 0 1 2 2v12a2 2 0 0 1 -2 2H4a2 2 0 0 1 -2 -2Z");
}

.v8c0ocbfs {
  d: path("M4 14h7");
}

</style>
