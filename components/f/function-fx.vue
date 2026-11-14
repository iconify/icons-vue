<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ka_kvwb0n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:function-fx" /></template>
<style>
.ka_kvwb0n {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M11 4.5c-1.5-1-3-.25-3.25 1.5L6.5 17.5C6.3 19.25 5.25 19.75 4 19m.5-8.5h6m3 1l7 7.5m0-7.5l-7 7.5");
}

</style>
