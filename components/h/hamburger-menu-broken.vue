<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="c_wyezbbg"/><path class="ihwi1gbya"/><path class="zj3_xl2hb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:hamburger-menu-broken" /></template>
<style>
.c_wyezbbg {
  d: path("M4 7L7 7M11 7L20 7");
}

.ihwi1gbya {
  d: path("M20 17H17M13 17L4 17");
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.zj3_xl2hb {
  d: path("M4 12H7L20 12");
}

</style>
