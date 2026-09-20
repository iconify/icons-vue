<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="jklm2rbet"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:document-text-extract-20-regular" /></template>
<style>
.jklm2rbet {
  fill: currentColor;
  d: path("M6 2a2 2 0 0 0-2 2v7h1V4a1 1 0 0 1 1-1h4v3.5A1.5 1.5 0 0 0 11.5 8H15v8a1 1 0 0 1-1 1H6a1 1 0 0 1-1-1v-2H4v2a2 2 0 0 0 2 2h8a2 2 0 0 0 2-2V7.414a1.5 1.5 0 0 0-.44-1.06l-3.914-3.915A1.5 1.5 0 0 0 10.586 2zm8.793 5H11.5a.5.5 0 0 1-.5-.5V3.207zM6.5 10a.5.5 0 0 0 0 1h7a.5.5 0 0 0 0-1zm-4 2a.5.5 0 0 0 0 1h7a.5.5 0 0 0 0-1zm4 2a.5.5 0 0 0 0 1h7a.5.5 0 0 0 0-1z");
}

</style>
