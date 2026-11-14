<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="scy0hr3hh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:kids-toothpaste" /></template>
<style>
.scy0hr3hh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m5.422 13.08l6.254-4.391a1.5 1.5 0 0 1 1.922.167l1.753 1.753a1.5 1.5 0 0 1 .167 1.922l-4.391 6.254a.495.495 0 0 1-.895-.214l-.026-.187a1.5 1.5 0 0 0-1.191-1.259l-.631-.126a1.5 1.5 0 0 1-1.176-1.176l-.126-.631a1.5 1.5 0 0 0-1.259-1.19l-.187-.027a.495.495 0 0 1-.214-.895m7.992-6.883l.707-.707a1.75 1.75 0 0 1 2.475 0l2.122 2.121a1.75 1.75 0 0 1 0 2.475l-.708.707a1.75 1.75 0 0 1-2.474 0l-2.122-2.121a1.75 1.75 0 0 1 0-2.475M15.75 4.5A2.25 2.25 0 0 1 19 7.75");
}

</style>
