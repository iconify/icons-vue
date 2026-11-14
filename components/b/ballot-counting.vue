<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pea383bnu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:ballot-counting" /></template>
<style>
.pea383bnu {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8 3h8a3.5 3.5 0 0 1 3.5 3.5v11A3.5 3.5 0 0 1 16 21H8a3.5 3.5 0 0 1-3.5-3.5v-11A3.5 3.5 0 0 1 8 3m-.25 5v8m2.75-8v8m2.75-8v8M16 8v8m-9.5-1l10.75-6");
}

</style>
