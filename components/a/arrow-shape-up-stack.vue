<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ch9wtc8lo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:arrow-shape-up-stack" /></template>
<style>
.ch9wtc8lo {
  fill: currentColor;
  d: path("M9 20v-3H4l8-9l8 9h-5v3zm-5-8l8-9l8 9h-2.675L12 6l-5.325 6z");
}

</style>
