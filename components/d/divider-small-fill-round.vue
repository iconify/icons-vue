<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="er3-szkyi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:divider-small-fill-round" /></template>
<style>
.er3-szkyi {
  fill: currentColor;
  d: path("M13 9v6a1 1 0 0 1-2 0V9a1 1 0 0 1 2 0");
}

</style>
