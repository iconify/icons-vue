<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="abb9xwfof"/><path class="atrqakbcy"/><path class="s6jbysbtk"/><path class="h-_fm4bbo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:chevrons-left-right-duotone-thin" /></template>
<style>
.abb9xwfof {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m9 7 -5 5 5 5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.atrqakbcy {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m15 7 5 5 -5 5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.h-_fm4bbo {
  d: path("m15 7 5 5 -5 5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.s6jbysbtk {
  d: path("m9 7 -5 5 5 5");
}

</style>
