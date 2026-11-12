<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w4tcujbcb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:git-stash-fill-sharp" /></template>
<style>
.w4tcujbcb {
  fill: currentColor;
  d: path("M13 8.829v3.757l1.293-1.293a.999.999 0 1 1 1.414 1.414l-3 3a1 1 0 0 1-1.414 0l-3-3a.999.999 0 1 1 1.414-1.414L11 12.586V8.829a3 3 0 1 1 2 0M2 14a1 1 0 0 1 2 0v6h16v-6a1 1 0 0 1 2 0v7a1 1 0 0 1-1 1H3a1 1 0 0 1-1-1Z");
}

</style>
