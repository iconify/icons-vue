<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gj14bacvx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:grid-alt-fill-round" /></template>
<style>
.gj14bacvx {
  fill: currentColor;
  d: path("M8 8H3a5 5 0 0 1 5-5Zm2 0V3h4v5Zm6 0V3a5 5 0 0 1 5 5ZM3 10h5v4H3Zm11 0v4h-4v-4Zm7 4h-5v-4h5ZM8 16v5a5 5 0 0 1-5-5Zm2 5v-5h4v5Zm6 0v-5h5a5 5 0 0 1-1.464 3.536A5 5 0 0 1 16 21");
}

</style>
