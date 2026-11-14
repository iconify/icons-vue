<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="cle-vebav"/><path class="s3781acdv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:clan-banner" /></template>
<style>
.cle-vebav {
  d: path("M5 3.25h14m-12.5 0v11.5h11V3.25M12 14.75v6");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.s3781acdv {
  d: path("M9.25 8.25L12 11l2.75-2.75");
}

</style>
