<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ed7z7vbhd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:air-conditioner-off-fill-round" /></template>
<style>
.ed7z7vbhd {
  fill: currentColor;
  d: path("M7 2h10a5 5 0 0 1 0 10H7A5 5 0 0 1 7 2m0 5a1 1 0 0 0 0 2h10a1 1 0 0 0 0-2Z");
}

</style>
