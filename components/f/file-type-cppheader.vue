<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="of1os9b5l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:file-type-cppheader" /></template>
<style>
.of1os9b5l {
  fill: var(--svg-color--984c93, #984c93);
  d: path("M2 25V7h3.6v5.9c1-1.2 2.5-1.8 4.3-1.8c1.5 0 2.8.5 3.6 1.5c.7.9 1 2.2 1 4.2V25h-3.6v-7.6q0-1.65-.6-2.4c-.4-.5-1.1-.7-1.9-.7c-.9 0-1.7.3-2.2.9c-.4.5-.6 1.4-.6 2.6V25Zm15.11-10.17v-2.34h2.35v2.34h2.34v2.34h-2.34v2.35h-2.35v-2.35h-2.34v-2.34zm8.2 0v-2.34h2.35v2.34H30v2.34h-2.34v2.35h-2.35v-2.35h-2.34v-2.34z");
}

</style>
