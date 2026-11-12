<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="fvnj3qbjd"/><path class="kh_4bzbdf"/><path class="o2bnwltsv"/><path class="r9gp_ab3d"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:list-vertical-linear" /></template>
<style>
.fvnj3qbjd {
  d: path("M4 17H11");
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.kh_4bzbdf {
  d: path("M4 12L11 12");
}

.o2bnwltsv {
  d: path("M4 7L11 7");
}

.r9gp_ab3d {
  stroke-linejoin: round;
  d: path("M17 4L17 20M20 8L17 4L14 8M14 16L17 20L20 16");
}

</style>
