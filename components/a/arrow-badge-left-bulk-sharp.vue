<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hgde5qbun"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:arrow-badge-left-bulk-sharp" /></template>
<style>
.hgde5qbun {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M11 20a1 1 0 0 1-.707-.293l-7-7a1 1 0 0 1 0-1.414l7-7A1 1 0 0 1 11 4h9a1.002 1.002 0 0 1 .707 1.707L14.414 12l6.293 6.293A1 1 0 0 1 20 20Z");
}

</style>
