<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pcyt748_v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:component-description" /></template>
<style>
.pcyt748_v {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m13.856 4.606l1.788 1.788a2.625 2.625 0 0 1 0 3.712l-1.788 1.788a2.625 2.625 0 0 1-3.712 0l-1.788-1.788a2.625 2.625 0 0 1 0-3.712l1.788-1.788a2.625 2.625 0 0 1 3.712 0M4 17.25h16M4 21h10");
}

</style>
