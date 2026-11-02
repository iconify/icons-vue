<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ixaw-ldqz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:letter-l-bulk-sharp" /></template>
<style>
.ixaw-ldqz {
  fill: currentColor;
  d: path("M8 19h9a1 1 0 0 1 0 2H7a1 1 0 0 1-1-1V4a1 1 0 0 1 2 0Z");
}

</style>
