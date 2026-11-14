<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s-cmvmbys"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:flash-fill" /></template>
<style>
.s-cmvmbys {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8.071 5.739L4.8 10.1A1.5 1.5 0 0 0 6 12.5h1.13a1.5 1.5 0 0 1 1.464 1.825L8 17a.886.886 0 0 0 1.597.691l3.424-5.022a1.387 1.387 0 0 0-1.146-2.169h-.872a1.5 1.5 0 0 1-1.482-1.732L9.875 6.5a1.009 1.009 0 0 0-1.804-.761M15.75 17.75a2 2 0 1 0 4 0a2 2 0 1 0-4 0m2-2V13.5m0 6.25V22m-2-4.25H13.5m6.25 0H22m-5.75-1.5L15 15m4.25 1.25L20.5 15m-4.25 4.25L15 20.5m4.25-1.25l1.25 1.25");
}

</style>
