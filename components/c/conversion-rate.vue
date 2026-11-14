<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j6zabzuyp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:conversion-rate" /></template>
<style>
.j6zabzuyp {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.953 3.5h8.094a1.75 1.75 0 0 1 1.411 2.785l-3.119 4.253A1.75 1.75 0 0 0 12 11.573v5.691a1.382 1.382 0 0 1-2 1.236l-1.033-.516A1.75 1.75 0 0 1 8 16.418v-4.845a1.75 1.75 0 0 0-.339-1.035L4.542 6.285A1.75 1.75 0 0 1 5.953 3.5m8.797 17.75l6.5-6.5m-5.75.75h.01m4.99 5h.01");
}

</style>
