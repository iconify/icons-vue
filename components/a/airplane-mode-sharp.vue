<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fkmon0bfy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:airplane-mode-sharp" /></template>
<style>
.fkmon0bfy {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m20.03 3.78l.19.19l.53.53l-.51.55l-3.23 3.4l-.51.55l.2.72l2.35 8.31l.2.72l-.53.53l-.44.44l-.53.53l-.38-.64l-3.99-6.72l-.38-.64l-.51.55l-2.73 2.9l-.51.55l.05.75l.15 2l.05.75l-.5.5l-.5.5l-.39-.64l-1.22-1.97l-.39-.64l-.64-.39l-1.97-1.22l-.64-.39l.5-.5l.5-.5l.75.05l2 .15l.75.05l.55-.51l2.9-2.73l.55-.51l-.64-.38l-6.72-3.99l-.64-.38l.53-.53l.44-.44l.53-.53l.72.22l8.31 2.56l.72.22l.53-.53l3.44-3.44l.53-.53z");
}

</style>
