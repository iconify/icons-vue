<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="os5nteb1t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:leaf-dew" /></template>
<style>
.os5nteb1t {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12.843 17.23c-2.123.999-4.669 1.52-7.593 1.52c0-9.5 5.5-15 15-15c0 2.808-.481 5.267-1.403 7.337M3.75 20.25l1.5-1.5m0 0l8.25-8.25m4.5 3.25s-2.5 2.75-2.5 4.75a2.5 2.5 0 0 0 5 0c0-2-2.5-4.75-2.5-4.75");
}

</style>
