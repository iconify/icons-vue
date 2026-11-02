<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hbgvvbcmp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:column-minus-fill" /></template>
<style>
.hbgvvbcmp {
  fill: currentColor;
  d: path("M3 6a3 3 0 0 1 3-3h2a3 3 0 0 1 3 3v12a3 3 0 0 1-3 3H6a3 3 0 0 1-3-3Zm17 5a1 1 0 0 1 0 2h-6a1 1 0 0 1 0-2Z");
}

</style>
