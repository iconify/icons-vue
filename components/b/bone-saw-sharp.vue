<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u5ncgm8yc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:bone-saw-sharp" /></template>
<style>
.u5ncgm8yc {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10.25 6h11v5.5h-4v9.75h-4.5V11.5h-2.5Zm4.25 2.75h4.25m-10.23.19l-3.37 2.83l-.23.19l.01-.3v-.41l.01-.3l-.26-.14l-.37-.2l-.26-.15l.11-.28l.15-.39l.11-.28l-.2-.22l-.27-.31l-.2-.23l.2-.23l.27-.31l.2-.22l-.11-.28l-.15-.39l-.11-.28l.26-.15l.37-.2l.26-.14l-.01-.3v-.41l-.01-.3l.23.19l3.37 2.83l.23.19z");
}

</style>
