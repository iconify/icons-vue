<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ruw4ycbmp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:crop-portrait-outline-sharp" /></template>
<style>
.ruw4ycbmp {
  fill: currentColor;
  d: path("M4 22V2h16v20zm2-2h12V4H6zm0 0V4z");
}

</style>
