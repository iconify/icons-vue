<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="vm_a1jbnu"/><path class="nplz63fbj"/><path class="to8m3ibcr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:gearbox-sharp" /></template>
<style>
.nplz63fbj {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M11.29 8.69v-.53l.01-.5h1.4l.01.5v.53l.01.5l.38.16l.38.16l.36-.35l.38-.38l.36-.35l.35.36l.28.28l.36.35l-.35.36l-.38.38l-.35.36l.16.38l.16.38l.5.01h.53l.5.01v1.4l-.5.01h-.53l-.5.01l-.16.38l-.16.38l.35.36l.38.38l.35.36l-.36.35l-.28.28l-.35.36l-.36-.35l-.38-.38l-.36-.35l-.38.16l-.38.16l-.01.5v.53l-.01.5h-1.4l-.01-.5v-.53l-.01-.5l-.38-.16l-.38-.16l-.36.35l-.38.38l-.36.35l-.35-.36l-.28-.28l-.36-.35l.35-.36l.38-.38l.35-.36l-.16-.38l-.16-.38l-.5-.01h-.53l-.5-.01v-1.4l.5-.01h.53l.5-.01l.16-.38l.16-.38l-.35-.36l-.38-.38l-.35-.36l.36-.35l.28-.28l.35-.36l.36.35l.38.38l.36.35l.38-.16l.38-.16z");
}

.to8m3ibcr {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 12h.01");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

.vm_a1jbnu {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.5 5.5h13v13h-13zM2.75 12H5.5m13 0h2.75");
}

</style>
