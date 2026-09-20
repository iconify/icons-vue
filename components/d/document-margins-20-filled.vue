<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="z7k3bybob"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:document-margins-20-filled" /></template>
<style>
.z7k3bybob {
  fill: currentColor;
  d: path("M6 2a2 2 0 0 0-2 2v12a2 2 0 0 0 2 2v-3.5a.5.5 0 0 1 1 0V18h6v-3.5a.5.5 0 0 1 1 0V18a2 2 0 0 0 2-2V4a2 2 0 0 0-2-2v3.5a.5.5 0 0 1-1 0V2H7v3.5a.5.5 0 0 1-1 0zm.5 11a.5.5 0 0 1-.5-.5v-5a.5.5 0 0 1 1 0v5a.5.5 0 0 1-.5.5m7 0a.5.5 0 0 1-.5-.5v-5a.5.5 0 0 1 1 0v5a.5.5 0 0 1-.5.5");
}

</style>
