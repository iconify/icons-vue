<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kr_gmwfzr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:column-pillar" /></template>
<style>
.kr_gmwfzr {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7.51 2.5h8.98a1.145 1.145 0 0 1 .76 2l-1.824 1.621a1.5 1.5 0 0 1-.996.379H9.57a1.5 1.5 0 0 1-.996-.379L6.75 4.5a1.145 1.145 0 0 1 .76-2M9 6.5V16l-2 2.5m8-12V16l2 2.5m-11 0h12a1.5 1.5 0 0 1 1.5 1.5a1.5 1.5 0 0 1-1.5 1.5H6A1.5 1.5 0 0 1 4.5 20A1.5 1.5 0 0 1 6 18.5");
}

</style>
