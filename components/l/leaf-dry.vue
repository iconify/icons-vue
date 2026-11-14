<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wj17dxbrq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:leaf-dry" /></template>
<style>
.wj17dxbrq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m4.878 17.779l-.294-2.937a1.5 1.5 0 0 1 .593-1.35l.723-.542a1.5 1.5 0 0 0 .6-1.2v-1.669a1.5 1.5 0 0 1 1.026-1.423l1.262-.421a1.5 1.5 0 0 0 .949-.949l.421-1.262A1.5 1.5 0 0 1 11.581 5H13.5a1.5 1.5 0 0 0 .9-.3l1.004-.753a1.5 1.5 0 0 1 1.312-.242l1.983.566a1.5 1.5 0 0 1 1.03 1.03l.566 1.983a1.5 1.5 0 0 1-.242 1.312L19.3 9.6a1.5 1.5 0 0 0-.3.9v1.919a1.5 1.5 0 0 1-1.026 1.423l-1.262.421a1.5 1.5 0 0 0-.949.949l-.446 1.338a1.5 1.5 0 0 1-1.316 1.021l-1.876.134a1.5 1.5 0 0 0-1.032.52l-.584.681a1.5 1.5 0 0 1-1.288.516l-3-.3a1.5 1.5 0 0 1-1.343-1.343M3.5 20.5L13 11");
}

</style>
