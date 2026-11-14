<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="v0bfx6s3f"/><path class="dylbr1d4e"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:dog-kennel-run" /></template>
<style>
.dylbr1d4e {
  d: path("M9 21v-5a3 3 0 0 1 6 0v5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.v0bfx6s3f {
  d: path("m4.553 9.981l6.25-5.859a1.75 1.75 0 0 1 2.394 0l6.25 5.859A1.75 1.75 0 0 1 20 11.258v7.992A1.75 1.75 0 0 1 18.25 21H5.75A1.75 1.75 0 0 1 4 19.25v-7.992a1.75 1.75 0 0 1 .553-1.277");
}

</style>
