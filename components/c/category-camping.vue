<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="x28l2hb5n"/><path class="ybpe0hbrk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:category-camping" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.x28l2hb5n {
  d: path("m4.07 17.357l6.425-10.823a1.75 1.75 0 0 1 3.01 0l6.425 10.823A1.75 1.75 0 0 1 18.426 20H5.574a1.75 1.75 0 0 1-1.504-2.643");
}

.ybpe0hbrk {
  d: path("m9.5 20l2.5-7l2.5 7");
}

</style>
