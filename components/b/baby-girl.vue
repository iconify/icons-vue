<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rwzc91bld"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:baby-girl" /></template>
<style>
.rwzc91bld {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5 14.5a7 7 0 1 0 14 0a7 7 0 1 0-14 0M7.897 3.132l8.206 2.736A1.442 1.442 0 0 0 18 4.5a1.442 1.442 0 0 0-1.897-1.368L7.897 5.868A1.442 1.442 0 0 1 6 4.5a1.442 1.442 0 0 1 1.897-1.368M12 4.5h.01M9.5 15h.01m4.99 0h.01");
}

</style>
