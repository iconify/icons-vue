<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u9k8t908b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:lighthouse-tower-sharp" /></template>
<style>
.u9k8t908b {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m8.33 20.5l1.09-10.25l.08-.75h5l.08.75l1.09 10.25l.08.75h-7.5zm-.83-11h9M9.75 6.15V5l.42-.42l1.41-1.41l.42-.42l.42.42l1.41 1.41l.42.42v1.75h-4.5zm-.65 7.1h5.8M8.7 17h6.6M2.75 4.5L6.5 5.75M21.25 4.5L17.5 5.75");
}

</style>
