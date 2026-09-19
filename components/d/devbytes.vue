<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="htft47b4g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:devbytes" /></template>
<style>
.htft47b4g {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m38.055 30.023l-26.84-12.509a2.2 2.2 0 0 1-1.27-1.992V6.6c0-.804.835-1.335 1.563-.996l26.547 12.373zM25.13 24l-13.915 6.486a2.2 2.2 0 0 0-1.27 1.992V41.4c0 .804.835 1.335 1.563.996l26.547-12.373");
}

</style>
