<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="jlaxo8b2l"/><path class="i_xl_f7ch"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:graduation-scroll" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.i_xl_f7ch {
  d: path("M15.56 4.56a2.75 1.5 45 0 0 3.88 3.88m-9.38 1.62l3.88 3.88m0 0c6.89-1.22 6.34 2.96 0 0m0 0c2.96 6.34-1.22 6.89 0 0");
}

.jlaxo8b2l {
  d: path("m8.44 19.44l11-11a2.75 1.5 45 0 0-3.88-3.88l-11 11a2.75 1.5 45 0 0 3.88 3.88");
}

</style>
