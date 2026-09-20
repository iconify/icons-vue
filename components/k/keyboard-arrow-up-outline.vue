<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wumpg3bps"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:keyboard-arrow-up-outline" /></template>
<style>
.wumpg3bps {
  fill: currentColor;
  d: path("m12 10.108l-4.6 4.6L6.692 14L12 8.692L17.308 14l-.708.708z");
}

</style>
