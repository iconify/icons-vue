<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="fc6ld8j4m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:file-type-cpp2" /></template>
<style>
.fc6ld8j4m {
  fill: var(--svg-color--005f91, #005f91);
  d: path("M26.914 13.8v1.54h-1.542v1.543h1.542v1.543h1.543v-1.543H30V15.34h-1.543V13.8Zm-3.5 0H21.87v1.54h-1.543v1.543h1.543v1.543h1.543v-1.543h1.543V15.34h-1.543Zm-3.654 5.226a6.167 6.167 0 1 1-.04-6.118l5.39-3.1a12.384 12.384 0 1 0 .032 12.34Z");
}

</style>
