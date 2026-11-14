<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="w14p-rbys"/><path class="d8pel1bks"/><path class="ju3_uldgo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:assignment-submission" /></template>
<style>
.d8pel1bks {
  d: path("M7 3h6.5L17 6.5V17H7Zm5 11V8");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ju3_uldgo {
  d: path("M9.75 10.25L12 8l2.25 2.25");
}

.w14p-rbys {
  d: path("M3 13v6a2 2 0 0 0 2 2h14a2 2 0 0 0 2-2v-6");
}

</style>
