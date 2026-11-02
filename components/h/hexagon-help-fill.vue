<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o8xp3hfmu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:hexagon-help-fill" /></template>
<style>
.o8xp3hfmu {
  fill: currentColor;
  d: path("M21 15.764a3 3 0 0 1-1.658 2.683l-6 3a3 3 0 0 1-2.684 0l-6-3A3 3 0 0 1 3 15.764V8.236a3 3 0 0 1 1.658-2.683l6-3a3 3 0 0 1 2.684 0l6 3A3 3 0 0 1 21 8.236ZM9 11a1 1 0 0 0 2 0a1.001 1.001 0 0 1 1.707-.707a1 1 0 0 1 .215 1.094A.99.99 0 0 1 12 12a1 1 0 0 0 0 2a3 3 0 1 0-3-3m3 4a1 1 0 0 0 0 2h.01a1 1 0 0 0 0-2Z");
}

</style>
