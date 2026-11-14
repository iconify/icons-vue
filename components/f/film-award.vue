<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h2p65wb5n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:film-award" /></template>
<style>
.h2p65wb5n {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m12 2.5l1.616 3.775l4.09.371l-3.091 2.704l.912 4.004L12 11.25l-3.527 2.104l.912-4.004l-3.091-2.704l4.09-.371Zm-4.5 15h9V21h-9ZM12 14v3.5");
}

</style>
