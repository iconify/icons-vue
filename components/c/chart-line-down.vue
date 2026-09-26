<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m9zk82b1u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:chart-line-down" /></template>
<style>
.m9zk82b1u {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M3 3L3 19C3 20.1046 3.8954 21 5 21L21 21M7 8L10.3887 11.8123C10.7342 12.201 11.32 12.26 11.7361 11.9479L14.3361 9.998C14.721 9.7092 15.2571 9.7356 15.6118 10.0608L20.2628 14.3243M16.5 15L20.5 15C20.7761 15 21 14.7761 21 14.5L21 10.5");
}

</style>
