<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="vd8fickdl"/><path class="ckk0akbag"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:dog-friendly-store" /></template>
<style>
.ckk0akbag {
  d: path("M8 5.5c-3-1-5.5 1-5.5 4c0 2.5 1.25 4 2.75 4l1.5-3m9.25-5c3-1 5.5 1 5.5 4c0 1.283-.329 2.302-.852 2.991m-2.322.161L17.25 10.5M10 10.25h.01m3.99 0h.01m-1.623 4.592q-.062.036-.129.06t-.137.035t-.142.009t-.14-.016t-.135-.043q-.066-.027-.126-.066q-.059-.039-.11-.089t-.093-.107q-.044-.062-.07-.134q-.026-.071-.032-.148q-.006-.076.01-.15q.015-.075.05-.143t.087-.124t.117-.095t.138-.06q.074-.021.15-.021h.35q.076 0 .15.021q.073.02.138.06t.117.095t.087.124q.042.081.055.171M18 21.5l-2.75-2.75c-1-1-.75-3.5 1-3.5c1 0 1.5.75 1.75 1.25c.25-.5.75-1.25 1.75-1.25c1.75 0 2 2.5 1 3.5Z");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.vd8fickdl {
  d: path("M12.303 19.49q-.15.01-.303.01c-3 0-5.5-3-5.5-7c0-2.5.25-5.5 1.5-7s6.75-1.5 8 0s1.5 4.5 1.5 7l-.001.117");
}

</style>
