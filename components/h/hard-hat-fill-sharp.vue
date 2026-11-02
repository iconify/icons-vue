<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hykqulb8x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:hard-hat-fill-sharp" /></template>
<style>
.hykqulb8x {
  fill: currentColor;
  d: path("M20 11v4H4v-4a6.01 6.01 0 0 1 5-5.918V4a1 1 0 0 1 1-1h4a1 1 0 0 1 1 1v1.082A6.01 6.01 0 0 1 20 11M2 17h20v3a1 1 0 0 1-1 1H3a1 1 0 0 1-1-1Z");
}

</style>
