<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="b11tk1b-y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:document-margins-20-regular" /></template>
<style>
.b11tk1b-y {
  fill: currentColor;
  d: path("M6.5 13a.5.5 0 0 1-.5-.5v-5a.5.5 0 0 1 1 0v5a.5.5 0 0 1-.5.5m7 0a.5.5 0 0 1-.5-.5v-5a.5.5 0 0 1 1 0v5a.5.5 0 0 1-.5.5M4 4a2 2 0 0 1 2-2h8a2 2 0 0 1 2 2v12a2 2 0 0 1-2 2H6a2 2 0 0 1-2-2zm3-1v2.5a.5.5 0 0 1-1 0V3a1 1 0 0 0-1 1v12a1 1 0 0 0 1 1v-2.5a.5.5 0 0 1 1 0V17h6v-2.5a.5.5 0 0 1 1 0V17a1 1 0 0 0 1-1V4a1 1 0 0 0-1-1v2.5a.5.5 0 0 1-1 0V3z");
}

</style>
