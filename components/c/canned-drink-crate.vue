<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kivn9cc_h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:canned-drink-crate" /></template>
<style>
.kivn9cc_h {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.125 11h13.75a2.625 2.625 0 0 1 2.625 2.625v4.75A2.625 2.625 0 0 1 18.875 21H5.125A2.625 2.625 0 0 1 2.5 18.375v-4.75A2.625 2.625 0 0 1 5.125 11M4 11V5l.75-1.5h2L7.5 5v6m2.75 0V5L11 3.5h2l.75 1.5v6m2.75 0V5l.75-1.5h2L20 5v6M9.5 15.5h5");
}

</style>
