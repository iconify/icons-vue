<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="hxmv1nbab"/><path class="b1cec2bhb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:astrophysicist" /></template>
<style>
.b1cec2bhb {
  d: path("M15.25 20.25a4 2-45 0 0 5.5-5.5a4 2-45 0 0-5.5 5.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.hxmv1nbab {
  d: path("M12.372 20.5H4c-.6 0-1-.4-1-1c0-3.25 3.25-5.5 7.5-5.5c.682 0 1.339.058 1.96.169M6.5 7a4 4 0 1 0 8 0a4 4 0 1 0-8 0m8.75 7.75a4 2 45 0 0 5.5 5.5a4 2 45 0 0-5.5-5.5");
}

</style>
