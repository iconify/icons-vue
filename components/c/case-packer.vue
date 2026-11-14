<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="jd3k6i3ga"/><path class="n75tvbbbc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:case-packer" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jd3k6i3ga {
  d: path("M2.5 9L4 12.5v9h16v-9L21.5 9M4 12.5h16");
}

.n75tvbbbc {
  d: path("M11.625 2.5h.75A2.625 2.625 0 0 1 15 5.125v2a2.625 2.625 0 0 1-2.625 2.625h-.75A2.625 2.625 0 0 1 9 7.125v-2A2.625 2.625 0 0 1 11.625 2.5M9 5.25h6");
}

</style>
