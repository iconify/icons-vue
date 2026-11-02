<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nkd-xrbxa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:flag-triangle-fill" /></template>
<style>
.nkd-xrbxa {
  fill: currentColor;
  d: path("M5 5c0-1.265 1.076-2.164 2.298-2.167c.399-.001.793.092 1.149.273l8 4a2.116 2.116 0 0 1 0 3.788L7 15.618V21a1 1 0 0 1-2 0Z");
}

</style>
