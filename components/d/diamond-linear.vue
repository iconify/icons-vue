<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ui_ykbc5q"/><path class="v54zxacxy"/><path class="udrgjebqc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:diamond-linear" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.udrgjebqc {
  d: path("M9.2 3L8 9.4724L12 21.005L16 9.4724L14.8 3");
}

.ui_ykbc5q {
  d: path("M4.50023 6.25L6.02473 4.2682C6.48453 3.6704 6.71453 3.3715 7.09173 3.1857C7.46883 3 7.84603 3 8.60023 3H15.4002C16.1544 3 16.5316 3 16.9087 3.1857C17.2859 3.3715 17.5159 3.6704 17.9757 4.2682L21.0247 8.2318L21.0252 8.23242C21.4847 8.82981 21.7145 9.12863 21.7073 9.4943C21.7002 9.86 21.4588 10.1497 20.9759 10.7292L13.4086 19.8099C12.7447 20.6066 12.4127 21.005 12.0002 21.005C11.5877 21.005 11.2557 20.6066 10.5918 19.8099L3.02453 10.7292C2.54163 10.1497 2.30023 9.86 2.29313 9.4943C2.28594 9.12863 2.51577 8.82981 2.97525 8.23242L2.97573 8.2318L4.50023 6.25Z");
}

.v54zxacxy {
  d: path("M2.29297 9.47217H21.7074");
}

</style>
