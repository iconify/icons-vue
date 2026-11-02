<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z7u1fl40y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:cpu-fill" /></template>
<style>
.z7u1fl40y {
  fill: currentColor;
  d: path("M11 3v2h2V3a1 1 0 0 1 2 0v2h1a3 3 0 0 1 3 3v1h2a1 1 0 0 1 0 2h-2v2h2a1 1 0 0 1 0 2h-2v1a3 3 0 0 1-3 3h-1v2a1 1 0 0 1-2 0v-2h-2v2a1 1 0 0 1-2 0v-2H8a3 3 0 0 1-3-3v-1H3a1 1 0 0 1 0-2h2v-2H3a1 1 0 0 1 0-2h2V8a3 3 0 0 1 3-3h1V3a1 1 0 0 1 2 0m-2 8v2a2 2 0 0 0 2 2h2a2 2 0 0 0 2-2v-2a2 2 0 0 0-2-2h-2a2 2 0 0 0-2 2");
}

</style>
