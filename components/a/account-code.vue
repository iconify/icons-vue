<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="avb_z5hcy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:account-code" /></template>
<style>
.avb_z5hcy {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m13.741 5.255l3.992 3.992a2.625 2.625 0 0 1 0 3.713l-4.773 4.773a2.625 2.625 0 0 1-3.713 0l-3.992-3.992a2.63 2.63 0 0 1-.758-2.094l.398-4.375a2.625 2.625 0 0 1 2.377-2.377l4.375-.398a2.63 2.63 0 0 1 2.094.758m-5.466 3.02h.01m4.056 1.238l2.475 2.474m-5.303.354l2.474 2.475");
}

</style>
