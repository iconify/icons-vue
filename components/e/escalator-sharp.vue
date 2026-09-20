<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y1twhabzr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:escalator-sharp" /></template>
<style>
.y1twhabzr {
  fill: currentColor;
  d: path("M6.385 17.116h3.454l5-9h2.776V6.885h-3.453l-5 9H6.384zM4 20V4h16v16z");
}

</style>
