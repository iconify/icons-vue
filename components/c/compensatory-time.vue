<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ekf2s55jf"/><path class="isz9jzgap"/><path class="ygbp8i1xm"/><path class="qwx-37bci"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:compensatory-time" /></template>
<style>
.ekf2s55jf {
  d: path("M2.5 15H6l4 2.5h4.25a1.25 1.25 0 0 1 0 2.5H9.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.isz9jzgap {
  d: path("M2.5 21.5H13l7.25-4.75c1-.75.25-2.25-1-1.75l-3.75 2.5M11 7a4.5 4.5 0 1 0 9 0a4.5 4.5 0 1 0-9 0");
}

.qwx-37bci {
  d: path("M2.75 10L5 12.25l2.25-1.75");
}

.ygbp8i1xm {
  d: path("M15.5 4.75V7L17 8M8.25 4.5C5 5 3.5 8 5 12");
}

</style>
