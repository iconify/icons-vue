<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m7i1izl8c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:drop-shadow-fill" /></template>
<style>
.m7i1izl8c {
  fill: currentColor;
  d: path("M5 2h8a3 3 0 0 1 3 3v8a3 3 0 0 1-3 3H5a3 3 0 0 1-3-3V5a3 3 0 0 1 3-3m14 18a1 1 0 0 0 1-1V7a1 1 0 0 1 2 0v12a3 3 0 0 1-3 3H7a1 1 0 0 1 0-2Z");
}

</style>
