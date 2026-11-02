<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rs3y__bgt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:hospital-fill-sharp" /></template>
<style>
.rs3y__bgt {
  fill: currentColor;
  d: path("M21 22h-6v-5a1 1 0 0 0-1-1h-4a1 1 0 0 0-1 1v5H3a1 1 0 0 1 0-2h1V3a1 1 0 0 1 1-1h14a1 1 0 0 1 1 1v17h1a1 1 0 0 1 0 2M13 7a1 1 0 0 0-2 0v2H9a1 1 0 0 0 0 2h2v2a1 1 0 0 0 2 0v-2h2a1 1 0 0 0 0-2h-2Zm-2 11h2v4h-2Z");
}

</style>
