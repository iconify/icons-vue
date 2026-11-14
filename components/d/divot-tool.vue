<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z7ct3186d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:divot-tool" /></template>
<style>
.z7ct3186d {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M11.293 12.707za2.5 2.5 0 0 1 0 3.536l-2.829 2.828a2.5 2.5 0 0 1-3.535 0a2.5 2.5 0 0 1 0-3.535l2.828-2.829a2.5 2.5 0 0 1 3.536 0m6.01-8.839l-5.657 5.657m8.486-2.828l-5.657 5.657m-2.829-2.829l2.829 2.829m-1.414-1.415l-1.768 1.768");
}

</style>
