<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v085awbsy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:filter-and" /></template>
<style>
.v085awbsy {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.953 3.5h8.094a1.75 1.75 0 0 1 1.411 2.785l-3.119 4.253A1.75 1.75 0 0 0 12 11.573v5.691a1.382 1.382 0 0 1-2 1.236l-1.033-.516A1.75 1.75 0 0 1 8 16.418v-4.845a1.75 1.75 0 0 0-.339-1.035L4.542 6.285A1.75 1.75 0 0 1 5.953 3.5m15.297 18l-4.5-4.75c-.75-.75-.5-2 .75-2s1.5 1.25.5 2L16.25 18c-1.25.75-1.25 1.5-1 2.25s1 1.25 1.75 1.25c1.5 0 2.5-1 3.25-2.75");
}

</style>
