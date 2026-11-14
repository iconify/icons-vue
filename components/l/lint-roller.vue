<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f4n5fkbin"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:lint-roller" /></template>
<style>
.f4n5fkbin {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.75 2.5h10.5a3.25 3.25 0 0 1 3.25 3.25A3.25 3.25 0 0 1 17.25 9H6.75A3.25 3.25 0 0 1 3.5 5.75A3.25 3.25 0 0 1 6.75 2.5M12 9v4m0 0za1.5 1.5 0 0 1 1.5 1.5V20a1.5 1.5 0 0 1-1.5 1.5a1.5 1.5 0 0 1-1.5-1.5v-5.5A1.5 1.5 0 0 1 12 13m2.5-4l2 6.5h5V9m-2.75 3.25h.01");
}

</style>
