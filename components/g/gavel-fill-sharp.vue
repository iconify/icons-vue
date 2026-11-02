<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c6e70my5m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:gavel-fill-sharp" /></template>
<style>
.c6e70my5m {
  fill: currentColor;
  d: path("M3.293 16.293L10.586 9L9.293 7.707a1 1 0 0 1 0-1.414l4-4a1 1 0 0 1 1.414 0l7 7a1 1 0 0 1 0 1.414l-4 4a1 1 0 0 1-1.414 0L15 13.414l-7.293 7.293a3.121 3.121 0 1 1-4.414-4.414M13 21a1 1 0 0 1 0-2h8a1 1 0 0 1 0 2Z");
}

</style>
