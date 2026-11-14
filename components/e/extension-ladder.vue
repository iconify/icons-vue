<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j_z0wfavl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:extension-ladder" /></template>
<style>
.j_z0wfavl {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.5 2.5v19m8-19v19m-8-15h8m-8 5.5h8m-8 5.5h8m6-14v17M16 6l2.5-2.5L21 6m-5 12l2.5 2.5L21 18");
}

</style>
