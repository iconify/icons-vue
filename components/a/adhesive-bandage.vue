<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="hkcqb-jro"/><path class="llhffjb9y"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:adhesive-bandage" /></template>
<style>
.hkcqb-jro {
  d: path("m5.282 13.768l8.486-8.486a3.5 3.5 0 0 1 4.95 0a3.5 3.5 0 0 1 0 4.95l-8.486 8.486a3.5 3.5 0 0 1-4.95 0a3.5 3.5 0 0 1 0-4.95");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.llhffjb9y {
  d: path("m8.111 10.939l2.828-2.828a1.5 1.5 0 0 1 2.122 0l2.828 2.828a1.5 1.5 0 0 1 0 2.122l-2.828 2.828a1.5 1.5 0 0 1-2.122 0l-2.828-2.828a1.5 1.5 0 0 1 0-2.122");
}

</style>
