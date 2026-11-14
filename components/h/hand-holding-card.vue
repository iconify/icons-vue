<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="klfwaxbsh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:hand-holding-card" /></template>
<style>
.klfwaxbsh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m6.826 4.649l7.581-1.612a2.625 2.625 0 0 1 3.113 2.022l.676 3.179a2.625 2.625 0 0 1-2.022 3.113l-7.581 1.612a2.625 2.625 0 0 1-3.113-2.022l-.676-3.179a2.625 2.625 0 0 1 2.022-3.113M2.5 17h3l3 3.5h7l5-4.5c.75-.75 0-2-1-1.5l-3.75 3H11.5M4.882 8.129l12.716-2.703");
}

</style>
