<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="vcfrccx_n"/><path class="bu1nht1fd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:crescent-star-moon" /></template>
<style>
.bu1nht1fd {
  d: path("m17.875 7.5l.024.064a1.44 1.44 0 0 0 1.351.936a.414.414 0 0 1 .293.707l-.192.192a1.5 1.5 0 0 0-.395 1.425L19 11a.38.38 0 0 1-.589.401l-.039-.028a1.5 1.5 0 0 0-1.744 0l-.039.028A.38.38 0 0 1 16 11l.044-.176a1.5 1.5 0 0 0-.395-1.425l-.192-.192a.414.414 0 0 1 .293-.707a1.44 1.44 0 0 0 1.351-.936l.024-.064a.401.401 0 0 1 .75 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.vcfrccx_n {
  d: path("M13.75 3.5a8.75 8.75 0 1 0 6 12.25a7 7 0 1 1-6-12.25");
}

</style>
