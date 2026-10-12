<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="xzwjjq-dn"/><path class="pfbzi9b-v"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:invert-colors" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.pfbzi9b-v {
  d: path("M12 2.75c3.5 4 6.5 7.5 6.5 11a6.5 6.5 0 0 1-6.5 6.5Z");
}

.xzwjjq-dn {
  d: path("M12 2.75c3.5 4 6.5 7.5 6.5 11a6.5 6.5 0 0 1-13 0c0-3.5 3-7 6.5-11");
}

</style>
