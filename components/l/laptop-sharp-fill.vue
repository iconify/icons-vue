<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="mods8hi-d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:laptop-sharp-fill" /></template>
<style>
.mods8hi-d {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M3 15L3 4C3 3.4477 3.4477 3 4 3L20 3C20.5523 3 21 3.4477 21 4L21 15L22 15C22.5523 15 23 15.4477 23 16L23 20C23 20.5523 22.5523 21 22 21L2 21C1.4477 21 1 20.5523 1 20L1 16C1 15.4477 1.4477 15 2 15L3 15ZM3 17L3 19L21 19L21 17L3 17Z");
}

</style>
