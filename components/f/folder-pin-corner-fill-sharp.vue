<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zn98osb-q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:folder-pin-corner-fill-sharp" /></template>
<style>
.zn98osb-q {
  fill: currentColor;
  d: path("M10 3c.265 0 .52.105.707.293L12.414 5H21a1 1 0 0 1 1 1v2a1 1 0 0 1-1 1H9v11a1 1 0 0 1-1 1H3a1 1 0 0 1-1-1V4a1 1 0 0 1 1-1Zm10 9a1 1 0 0 1 0 2v1.586l1.707 1.707A1 1 0 0 1 21 19h-3v2a1 1 0 0 1-2 0v-2h-3a1.002 1.002 0 0 1-.707-1.707L14 15.586V14a1 1 0 0 1 0-2Z");
}

</style>
