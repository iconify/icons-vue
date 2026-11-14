<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pn4bnfbux"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:hanger-clips" /></template>
<style>
.pn4bnfbux {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 7V6a2 2 0 1 0-2-2M2.5 7h19v2.5h-19ZM6 9.5V12m-2 0h4v7.5H4Zm14-2.5V12m-2 0h4v7.5h-4ZM4 15.5h4m8 0h4");
}

</style>
