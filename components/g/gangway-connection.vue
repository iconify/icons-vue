<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hf_4bdbxb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:gangway-connection" /></template>
<style>
.hf_4bdbxb {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.125 5h.75A2.625 2.625 0 0 1 8.5 7.625v8.75A2.625 2.625 0 0 1 5.875 19h-.75A2.625 2.625 0 0 1 2.5 16.375v-8.75A2.625 2.625 0 0 1 5.125 5m13 0h.75A2.625 2.625 0 0 1 21.5 7.625v8.75A2.625 2.625 0 0 1 18.875 19h-.75a2.625 2.625 0 0 1-2.625-2.625v-8.75A2.625 2.625 0 0 1 18.125 5M8.5 8l1.75-1.5L12 8l1.75-1.5L15.5 8m-7 8l1.75 1.5L12 16l1.75 1.5L15.5 16");
}

</style>
