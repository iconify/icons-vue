<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c3jb06qfk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:hotfix" /></template>
<style>
.c3jb06qfk {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m5.75 16.25l5.75-5.75a4.5 4.5 0 0 1 6-6l-4 4a1.5 1.5 0 0 0 2 2l4-4a4.5 4.5 0 0 1-6 6l-5.75 5.75a1.5 1.5 0 0 1-2-2m12.33-.698l-1.757 2.007a.567.567 0 0 0 .427.941a.9.9 0 0 1 .855 1.186L17.5 20a.322.322 0 0 0 .546.314l1.96-2.22a.508.508 0 0 0-.381-.844a.94.94 0 0 1-.924-1.107l.049-.268a.386.386 0 0 0-.67-.323");
}

</style>
