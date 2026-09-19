<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="kgii1ibgb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:code-editor" /></template>
<style>
.kgii1ibgb {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M17.592 37.092L4.5 24l13.092-13.092m2.824 26.202l7.218-26.219m2.774.017L43.5 24L30.408 37.092");
}

</style>
