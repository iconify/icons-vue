<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="cn7leib4j"/><path class="mtki-ylue"/><path class="c-d9t2bgo"/><path class="og5qzjlhn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:block-stack" /></template>
<style>
.c-d9t2bgo {
  d: path("M3 14.75L7 17l4-2.25M7 17v4.5m10.735-8.586l2.5 1.406A1.5 1.5 0 0 1 21 15.627v2.746a1.5 1.5 0 0 1-.765 1.307l-2.5 1.406a1.5 1.5 0 0 1-1.47 0l-2.5-1.406A1.5 1.5 0 0 1 13 18.373v-2.746a1.5 1.5 0 0 1 .765-1.307l2.5-1.406a1.5 1.5 0 0 1 1.47 0");
}

.cn7leib4j {
  d: path("m12.735 2.414l2.5 1.406A1.5 1.5 0 0 1 16 5.127v2.746a1.5 1.5 0 0 1-.765 1.307l-2.5 1.406a1.5 1.5 0 0 1-1.47 0l-2.5-1.406A1.5 1.5 0 0 1 8 7.873V5.127a1.5 1.5 0 0 1 .765-1.307l2.5-1.406a1.5 1.5 0 0 1 1.47 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.mtki-ylue {
  d: path("m8 4.25l4 2.25l4-2.25M12 6.5V11m-4.265 1.914l2.5 1.406A1.5 1.5 0 0 1 11 15.627v2.746a1.5 1.5 0 0 1-.765 1.307l-2.5 1.406a1.5 1.5 0 0 1-1.47 0l-2.5-1.406A1.5 1.5 0 0 1 3 18.373v-2.746a1.5 1.5 0 0 1 .765-1.307l2.5-1.406a1.5 1.5 0 0 1 1.47 0");
}

.og5qzjlhn {
  d: path("M13 14.75L17 17l4-2.25M17 17v4.5");
}

</style>
