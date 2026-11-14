<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qfnrrybdk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:career-path" /></template>
<style>
.qfnrrybdk {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12.5 3h7.25l1.75 1.75l-1.75 1.75H12.5Zm8.25 6.25h-7.5L11.5 11l1.75 1.75h7.5ZM16.5 6.5v2.75m0 3.5v3.5m-14 5.25c4 0 7.25-.75 7.25-2.75s2.75-2.5 6.75-2.5");
}

</style>
