<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d3_d7hgfl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:image-minus-fill-round" /></template>
<style>
.d3_d7hgfl {
  fill: currentColor;
  d: path("m17.399 21.985l-6.692-6.692a5.24 5.24 0 0 0-7.414 0L2 16.586V7a5 5 0 0 1 5-5h10a5 5 0 0 1 5 5v10a5 5 0 0 1-4.601 4.985M18 8h-6a1 1 0 0 0 0 2h6a1 1 0 0 0 0-2M3.191 18.224l1.516-1.517a3.243 3.243 0 0 1 4.586 0L14.586 22H7a4.99 4.99 0 0 1-4.584-3.001Z");
}

</style>
