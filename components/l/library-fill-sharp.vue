<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s9437jbon"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:library-fill-sharp" /></template>
<style>
.s9437jbon {
  fill: currentColor;
  d: path("M7 2v20H4a1 1 0 0 1-1-1V3a1 1 0 0 1 1-1Zm2 0h3a1 1 0 0 1 1 1v.719l2.757-.689a1 1 0 0 1 1.213.727l4 16a1 1 0 0 1-.727 1.213l-4 1a1 1 0 0 1-1.213-.727L13 13.123V21a1 1 0 0 1-1 1H9Z");
}

</style>
