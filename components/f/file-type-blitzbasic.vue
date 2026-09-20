<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="wfoh7qbpo"/><path class="qpg4oeblx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:file-type-blitzbasic" /></template>
<style>
.qpg4oeblx {
  fill: var(--svg-color--00d8ff, #00d8ff);
  d: path("M16 9v3h1v7h-1v3h10v-1h1v-1h1v-4h-1v-1h1v-4h-1v-1h-1V9zm5 3h2v2h-2zm0 5h2v2h-2z");
}

.wfoh7qbpo {
  fill: var(--svg-color--00ffae, #00ffae);
  d: path("M4 9v3h1v7H4v3h10v-1h1v-1h1v-4h-1v-1h1v-4h-1v-1h-1V9zm6 3h2v2h-2zm0 5h2v2h-2z");
}

</style>
