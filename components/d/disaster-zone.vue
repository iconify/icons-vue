<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d9kz5fbqj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:disaster-zone" /></template>
<style>
.d9kz5fbqj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M14.459 2.824a9.5 9.5 0 0 1 6.717 6.717m0 4.918a9.5 9.5 0 0 1-6.717 6.717m-4.918 0a9.5 9.5 0 0 1-6.717-6.717m0-4.918a9.5 9.5 0 0 1 6.717-6.717m7.084 8.551l-.183-.061a1.5 1.5 0 0 1-.846-2.134l.029-.055a.554.554 0 0 0-.75-.75l-.055.029a1.5 1.5 0 0 1-2.134-.846l-.061-.183a.659.659 0 0 0-1.25 0l-.061.183a1.5 1.5 0 0 1-2.134.846l-.055-.029a.554.554 0 0 0-.75.75l.029.055a1.5 1.5 0 0 1-.846 2.134l-.183.061a.659.659 0 0 0 0 1.25l.183.061a1.5 1.5 0 0 1 .846 2.134l-.029.055a.554.554 0 0 0 .75.75l.055-.029a1.5 1.5 0 0 1 2.134.846l.061.183a.659.659 0 0 0 1.25 0l.061-.183a1.5 1.5 0 0 1 2.134-.846l.055.029a.554.554 0 0 0 .75-.75l-.029-.055a1.5 1.5 0 0 1 .846-2.134l.183-.061a.659.659 0 0 0 0-1.25");
}

</style>
