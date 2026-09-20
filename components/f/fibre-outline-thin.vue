<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="r7xk8o29f"/><path class="v4iyegbro"/><path class="xhssufbfj"/><path class="bydm5bjkj"/><path class="c3g7d7t3t"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:fibre-outline-thin" /></template>
<style>
.bydm5bjkj {
  d: path("m12 14 -4 -4");
}

.c3g7d7t3t {
  d: path("m12 14 4 -4");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.r7xk8o29f {
  d: path("M12 4v16");
}

.v4iyegbro {
  d: path("M12 9 8 5");
}

.xhssufbfj {
  d: path("m12 9 4 -4");
}

</style>
