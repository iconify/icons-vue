<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c4-jamgvm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:incident-response" /></template>
<style>
.c4-jamgvm {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.5 17.5v-5a5.5 5.5 0 0 1 11 0v5M4 17.5h16V21H4Zm8-15V4M4 5l1.25 1.25M20 5l-1.25 1.25M12 10.5V15m-2.25-2.25h4.5");
}

</style>
