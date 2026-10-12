<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="t3sgkl8bm"/><path class="vq9gfjb-n"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:first-aid-kit-plus" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.t3sgkl8bm {
  d: path("M7.5 8h9q2 0 2.41 1.96l1.93 9.33q.41 1.96-1.59 1.96H4.75q-2 0-1.59-1.96l1.93-9.33Q5.5 8 7.5 8M9 8V6.25a3 3 0 0 1 6 0V8m-8.5 3h11");
}

.vq9gfjb-n {
  d: path("M10.75 13.75h2.5V15h1.25v2.5h-1.25v1.25h-2.5V17.5H9.5V15h1.25Z");
}

</style>
