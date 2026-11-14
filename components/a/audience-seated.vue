<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ewnw-5b7i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:audience-seated" /></template>
<style>
.ewnw-5b7i {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.5 13za2.25 2.25 0 0 1 2.25 2.25v3A2.25 2.25 0 0 1 4.5 20.5a2.25 2.25 0 0 1-2.25-2.25v-3A2.25 2.25 0 0 1 4.5 13m7.5 0za2.25 2.25 0 0 1 2.25 2.25v3A2.25 2.25 0 0 1 12 20.5a2.25 2.25 0 0 1-2.25-2.25v-3A2.25 2.25 0 0 1 12 13m7.5 0za2.25 2.25 0 0 1 2.25 2.25v3a2.25 2.25 0 0 1-2.25 2.25a2.25 2.25 0 0 1-2.25-2.25v-3A2.25 2.25 0 0 1 19.5 13M2.25 10.25v-4.5a2.25 2.25 0 0 1 4.5 0v4.5m3 0v-4.5a2.25 2.25 0 0 1 4.5 0v4.5m3 0v-4.5a2.25 2.25 0 0 1 4.5 0v4.5");
}

</style>
