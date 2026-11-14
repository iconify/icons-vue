<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="esu3fio2v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:hand-gripper" /></template>
<style>
.esu3fio2v {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9.5 5a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0Zm-2.698 5.577l3.396.846l-2.419 9.703l-3.396-.846Zm7 .846l3.396-.846l2.419 9.703l-3.396.846ZM10.75 7.25L8.5 11m4.75-3.75L15.5 11");
}

</style>
