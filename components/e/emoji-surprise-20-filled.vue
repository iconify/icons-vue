<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ayz78bboa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:emoji-surprise-20-filled" /></template>
<style>
.ayz78bboa {
  fill: currentColor;
  d: path("M2 10a8 8 0 1 1 16 0a8 8 0 0 1-16 0m5.5-.5a1 1 0 1 0 0-2a1 1 0 0 0 0 2m4.25 3a1.75 1.75 0 1 0-3.5 0a1.75 1.75 0 0 0 3.5 0m.75-3a1 1 0 1 0 0-2a1 1 0 0 0 0 2");
}

</style>
