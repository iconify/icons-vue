<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tjhp8_bzp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:italic-bulk-sharp" /></template>
<style>
.tjhp8_bzp {
  fill: currentColor;
  d: path("M10 20H8a1 1 0 0 1 0-2h1.246l3.428-12H12a1 1 0 0 1 0-2h4a1 1 0 0 1 0 2h-1.246l-3.428 12H12a1 1 0 0 1 0 2Z");
}

</style>
