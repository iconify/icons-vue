<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uj418w8xb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:lock-off-fill-round" /></template>
<style>
.uj418w8xb {
  fill: currentColor;
  d: path("M16 6v3a5 5 0 0 1 5 5v3a5 5 0 0 1-.525 2.233L10.243 9H14V6a2 2 0 0 0-4 0a1 1 0 0 1-2 0a4 4 0 0 1 8 0M2.707 4.293l17 17a.999.999 0 1 1-1.414 1.414l-.903-.902c-.452.13-.92.196-1.39.195H8a5 5 0 0 1-5-5v-3c0-1.724.884-3.326 2.346-4.239L1.293 5.707a.999.999 0 1 1 1.414-1.414");
}

</style>
