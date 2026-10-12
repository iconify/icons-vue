<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="bo3t-gbpw"/><path class="ihfgmxmto"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:bud" /></template>
<style>
.bo3t-gbpw {
  d: path("M12 2.75c2.75 2.75 4.5 5.75 4.5 8.75a4.5 4.5 0 0 1-9 0c0-3 1.75-6 4.5-8.75");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ihfgmxmto {
  d: path("M7.6 10.25c2 .5 3.5 1.75 4.4 3.5c.9-1.75 2.4-3 4.4-3.5M12 16v5.25m0-.25c.5-2 2.25-3.25 5-3.25c-.5 2-2.25 3.25-5 3.25");
}

</style>
