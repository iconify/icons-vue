<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="psh1w61io"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:bring-to-front-20-filled" /></template>
<style>
.psh1w61io {
  fill: currentColor;
  d: path("M1 3a2 2 0 0 1 2-2h3a2 2 0 0 1 2 2v1h-.5q-.255 0-.5.035V3a1 1 0 0 0-1-1H3a1 1 0 0 0-1 1v3a1 1 0 0 0 1 1h1.035A3.5 3.5 0 0 0 4 7.5V8H3a2 2 0 0 1-2-2zm11 13v1a2 2 0 0 0 2 2h3a2 2 0 0 0 2-2v-3a2 2 0 0 0-2-2h-1v.5q0 .255-.035.5H17a1 1 0 0 1 1 1v3a1 1 0 0 1-1 1h-3a1 1 0 0 1-1-1v-1.035q-.245.035-.5.035zM5 7.5A2.5 2.5 0 0 1 7.5 5h5A2.5 2.5 0 0 1 15 7.5v5a2.5 2.5 0 0 1-2.5 2.5h-5A2.5 2.5 0 0 1 5 12.5z");
}

</style>
