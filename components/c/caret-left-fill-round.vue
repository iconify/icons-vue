<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k-q9q7b5g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:caret-left-fill-round" /></template>
<style>
.k-q9q7b5g {
  fill: currentColor;
  d: path("M15 8v8a1.002 1.002 0 0 1-1.707.707l-4-4a1 1 0 0 1 0-1.414l4-4A1 1 0 0 1 15 8");
}

</style>
