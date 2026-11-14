<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="o1cps1bqz"/><path class="o05bagdfy"/><path class="g-pgc9j9t"/><path class="jp0unjmdf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:colour-mixing-light" /></template>
<style>
.g-pgc9j9t {
  d: path("M10 15a5.5 5.5 0 1 0 11 0a5.5 5.5 0 1 0-11 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jp0unjmdf {
  fill: currentColor;
  d: path("M12 10.75a5.5 5.5 0 0 1 2 3.5a5.5 5.5 0 0 1-4 0a5.5 5.5 0 0 1 2-3.5");
}

.o05bagdfy {
  d: path("M3 15a5.5 5.5 0 1 0 11 0a5.5 5.5 0 1 0-11 0");
}

.o1cps1bqz {
  d: path("M6.5 9a5.5 5.5 0 1 0 11 0a5.5 5.5 0 1 0-11 0");
}

</style>
