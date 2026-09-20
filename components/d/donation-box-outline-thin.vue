<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="em8xf33qp"/><path class="rw6ho_bav"/><path class="vrecxx6kh"/><path class="h67kvlt_n"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:donation-box-outline-thin" /></template>
<style>
.em8xf33qp {
  d: path("M4 9v11h16V9");
}

.h67kvlt_n {
  d: path("M12 16c-2 -1.5 -4 -3 -3 -4.5 0.7 -1 2 -0.5 3 0.5 1 -1 2.3 -1.5 3 -0.5 1 1.5 -1 3 -3 4.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.rw6ho_bav {
  d: path("M2 9h20");
}

.vrecxx6kh {
  d: path("M9 6h6");
}

</style>
