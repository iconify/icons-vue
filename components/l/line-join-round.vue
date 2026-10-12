<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="wegw82bxm"/><path class="qr9-o6rkg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:line-join-round" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.qr9-o6rkg {
  d: path("M2.75 9.5h8.75v11.75");
}

.wegw82bxm {
  d: path("M2.75 5.25h8.75a4.25 4.25 0 0 1 4.25 4.25v11.75m-13-7.5h4.5v7.5");
}

</style>
