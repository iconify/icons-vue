<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r0wg_qb3e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:currency-bitcoin-fill-sharp" /></template>
<style>
.r0wg_qb3e {
  fill: currentColor;
  d: path("M8 3v1h2V3a1 1 0 0 1 2 0v1h1a4 4 0 0 1 4 4v1c0 .943-.329 1.851-.936 2.572A4 4 0 0 1 18 15v1a4 4 0 0 1-4 4h-2v1a1 1 0 0 1-2 0v-1H8v1a1 1 0 0 1-2 0V3a1 1 0 0 1 2 0m0 3v5h5a2 2 0 0 0 2-2V8a2 2 0 0 0-2-2Zm0 12h6a2 2 0 0 0 2-2v-1a2 2 0 0 0-2-2H8Z");
}

</style>
