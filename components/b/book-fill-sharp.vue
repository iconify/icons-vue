<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ef6mznbcp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:book-fill-sharp" /></template>
<style>
.ef6mznbcp {
  fill: currentColor;
  d: path("M4 19V3a1 1 0 0 1 1-1h14a1 1 0 0 1 1 1v14a1 1 0 0 1-1 1h-1v3a1 1 0 0 1-1 1H7a3 3 0 0 1-3-3m3-1a1 1 0 0 0 0 2h9v-2Z");
}

</style>
