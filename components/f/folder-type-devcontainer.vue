<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="scymv09xs"/><circle class="s9u60x19o"/><path class="e7ned-box"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:folder-type-devcontainer" /></template>
<style>
.e7ned-box {
  fill: var(--svg-color--add1ea, #add1ea);
  d: path("m17.269 25.816l-1.024-.996l2.419-2.488l-2.417-2.462l1.02-1.001l3.394 3.459zm7.603-2.601l1.024-.996l-2.419-2.488l2.417-2.462l-1.02-1.001l-3.394 3.459z");
}

.s9u60x19o {
  cx: 21px;
  cy: 21px;
  r: 10px;
  fill: var(--svg-color--193e63, #193e63);
}

.scymv09xs {
  fill: var(--svg-color--558fbf, #558fbf);
  d: path("M27.5 5.5h-9.3l-2.1 4.2H4.4v16.8h25.2v-21Zm0 4.2h-8.2l1.1-2.1h7.1Z");
}

</style>
