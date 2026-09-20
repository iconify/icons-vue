<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="xtda80_ez"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:file-type-light-shaderlab" /></template>
<style>
.xtda80_ez {
  fill: var(--svg-color--222c37, #222c37);
  d: path("m20.152 16l4.9-8.461L27.42 16l-2.368 8.46zm-2.388 1.374l4.9 8.46l-8.534-2.186l-6.166-6.273Zm4.9-11.21l-4.9 8.461h-9.8l6.166-6.273zm7 6.957L26.669 2L15.511 4.98l-1.652 2.9l-3.351-.02L2.341 16l8.167 8.139l3.35-.025l1.654 2.9L26.669 30l2.989-11.119L27.961 16l1.7-2.879Z");
}

</style>
