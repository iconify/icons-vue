<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="xvaihfybl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:file-type-stackblitz" /></template>
<style>
.xvaihfybl {
  fill: var(--svg-color--2196f3, #2196f3);
  d: path("M6.3 18.8h8.2L9.9 30l15.8-16.8h-8.2L22.1 2z");
}

</style>
