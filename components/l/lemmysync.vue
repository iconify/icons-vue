<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ljj6pxufb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:lemmysync" /></template>
<style>
.ljj6pxufb {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M18.47 42.5L5.91 25.62h25.41L18.47 42.5zm-1.73-19.92L29.22 5.5l12.87 17.08H16.74z");
}

</style>
