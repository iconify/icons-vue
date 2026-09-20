<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="rwa05hbab"/><path class="u6xminppf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:folder-type-junie" /></template>
<style>
.rwa05hbab {
  fill: var(--svg-color--b100b8, #b100b8);
  d: path("M27.417 5.5H18.19l-2.083 4.2H4.5v16.8h25v-21Zm0 4.2h-8.135l1.091-2.1h7.044Z");
}

.u6xminppf {
  fill: var(--svg-color--47e054, #47e054);
  d: path("M18 12h6v6h-6zm6 6h6v1c0 7-3 11-11 11h-1v-6h1c3.5 0 5-1.5 5-5zm-12 0h6v6h-6z");
}

</style>
