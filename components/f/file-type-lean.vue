<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="qnpt-26ug"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:file-type-lean" /></template>
<style>
.qnpt-26ug {
  fill: none;
  stroke: var(--svg-color--dedede, #dedede);
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("m3 3l13 25L29 3M10 16h12");
}

</style>
