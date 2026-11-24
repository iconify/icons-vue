<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h20bj6xmt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:lock-off-fill" /></template>
<style>
.h20bj6xmt {
  fill: currentColor;
  d: path("m2.707 2.293l19 19a.999.999 0 1 1-1.414 1.414l-1-.999A3 3 0 0 1 18 22H6a3 3 0 0 1-3-3v-8a3 3 0 0 1 2.611-2.975L1.293 3.707a.999.999 0 1 1 1.414-1.414M15 7a3 3 0 0 0-5.121-2.121a1 1 0 0 1-1.631-.325a1 1 0 0 1 .216-1.09A5.001 5.001 0 0 1 17 7v1h1a3 3 0 0 1 3 3v6.757L11.243 8H15Z");
}

</style>
