<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="g5bwgeb5z"/><path class="zviqef80j"/><path class="uqq4e9bxc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:blood-bag" /></template>
<style>
.g5bwgeb5z {
  d: path("M10.25 2.5h3.5A5.25 5.25 0 0 1 19 7.75v4.5a5.25 5.25 0 0 1-5.25 5.25h-3.5A5.25 5.25 0 0 1 5 12.25v-4.5a5.25 5.25 0 0 1 5.25-5.25m.25 2.75h3");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.uqq4e9bxc {
  d: path("M10 17.5v4m4-4v4");
}

.zviqef80j {
  fill: currentColor;
  d: path("M12 8c1.75 2 2.75 3.25 2.75 4.5C14.75 14 13.5 15 12 15s-2.75-1-2.75-2.5c0-1.25 1-2.5 2.75-4.5");
}

</style>
