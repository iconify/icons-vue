<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="gnnd0vbmk"/><path class="n0q0gac6b"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:hospital-wifi" /></template>
<style>
.gnnd0vbmk {
  d: path("M2.608 8.69a11.5 11.5 0 0 1 14.784 0M5.018 11.563a7.75 7.75 0 0 1 9.964 0m-7.553 2.873q.13-.109.269-.207q.138-.097.285-.183t.299-.158q.153-.073.312-.132t.322-.106q.163-.046.329-.078q.167-.032.336-.05q.168-.017.338-.021q.169-.003.338.008t.337.036t.333.064t.326.093t.317.119q.156.067.305.146q.15.08.293.171q.142.092.276.196M10 17.5h.01");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.n0q0gac6b {
  fill: currentColor;
  d: path("M16.5 14.25h3v2.25h2.25v3H19.5v2.25h-3V19.5h-2.25v-3h2.25Z");
}

</style>
