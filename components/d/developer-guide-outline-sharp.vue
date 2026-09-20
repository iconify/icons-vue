<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aufb6-82k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:developer-guide-outline-sharp" /></template>
<style>
.aufb6-82k {
  fill: currentColor;
  d: path("M3 21V3h18v18zM5 5v14h14V5h-2v7l-2.5-1.5L12 12V5zm0 14V5z");
}

</style>
