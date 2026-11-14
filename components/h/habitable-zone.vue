<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ttegd3s3w"/><path class="ziqxm9bjx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:habitable-zone" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ttegd3s3w {
  d: path("M21.25 10.25a9.5 9.5 0 1 1-7.5-7.5l-.75 3A6.25 6.25 0 1 0 18.25 11Z");
}

.ziqxm9bjx {
  d: path("M15.75 6.5a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0M12.5 9.75l.261.653a1.5 1.5 0 0 0 .836.836l.653.261a.539.539 0 0 1 0 1l-.653.261a1.5 1.5 0 0 0-.836.836l-.261.653a.539.539 0 0 1-1 0l-.261-.653a1.5 1.5 0 0 0-.836-.836L9.75 12.5a.539.539 0 0 1 0-1l.653-.261a1.5 1.5 0 0 0 .836-.836l.261-.653a.539.539 0 0 1 1 0");
}

</style>
