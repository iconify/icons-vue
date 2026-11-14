<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="zriqzobcm"/><path class="ivft77elz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:eye-ointment" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ivft77elz {
  d: path("m16.243 5.075l1.767 1.768a1.75 1.75 0 0 1 0 2.475l-.353.354a1.75 1.75 0 0 1-2.475 0l-1.768-1.768a1.75 1.75 0 0 1 0-2.475l.354-.354a1.75 1.75 0 0 1 2.475 0M5.282 12.5l5.304 5.303M14.5 18q3.5-5 7 0q-3.5 5-7 0m3.5 0h.01");
}

.zriqzobcm {
  d: path("m4.329 15.789l2.967 2.968a1.75 1.75 0 0 0 2.574-.107l5.509-6.512a1.75 1.75 0 0 0-.098-2.368l-1.966-1.965a1.75 1.75 0 0 0-2.367-.099l-6.512 5.51a1.75 1.75 0 0 0-.107 2.573");
}

</style>
