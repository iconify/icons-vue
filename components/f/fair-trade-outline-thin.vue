<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="r7xk8o29f"/><path class="k4qo1xe9v"/><path class="bai-ikdbm"/><path class="qorafhbcl"/><path class="qw7b_6b1t"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:fair-trade-outline-thin" /></template>
<style>
.bai-ikdbm {
  d: path("M9 6a3 3 0 0 1 -6 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.k4qo1xe9v {
  d: path("M4 6h16");
}

.qorafhbcl {
  d: path("M21 6a3 3 0 0 1 -6 0");
}

.qw7b_6b1t {
  d: path("M8 20h8");
}

.r7xk8o29f {
  d: path("M12 4v16");
}

</style>
