<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ljrg8ablw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:ethernet-fill" /></template>
<style>
.ljrg8ablw {
  fill: currentColor;
  d: path("M19 18h-1v2a2 2 0 0 1-2 2H8a2 2 0 0 1-2-2v-2H5a3 3 0 0 1-3-3V6a3 3 0 0 1 3-3h14a3 3 0 0 1 3 3v9a3 3 0 0 1-3 3M7 8a1 1 0 0 0-2 0v3a1 1 0 0 0 2 0Zm4 0a1 1 0 0 0-2 0v3a1 1 0 0 0 2 0Zm4 3V8a1 1 0 0 0-2 0v3a1 1 0 0 0 2 0m4-3a1 1 0 0 0-2 0v3a1 1 0 0 0 2 0Z");
}

</style>
