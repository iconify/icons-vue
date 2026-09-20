<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="f3r6jjb4a"/><path class="q7xe92bpy"/><path class="camhvtqcl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:align-end-vertical-outline-thin" /></template>
<style>
.camhvtqcl {
  d: path("M11 14h6v4h-6Z");
}

.f3r6jjb4a {
  d: path("M20 3v18");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.q7xe92bpy {
  d: path("M7 7h10v4H7Z");
}

</style>
