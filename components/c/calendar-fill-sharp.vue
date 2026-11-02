<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="di598xbtb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:calendar-fill-sharp" /></template>
<style>
.di598xbtb {
  fill: currentColor;
  d: path("M9 3v1h6V3a1 1 0 0 1 2 0v1h3a1 1 0 0 1 1 1v16a1 1 0 0 1-1 1H4a1 1 0 0 1-1-1V5a1 1 0 0 1 1-1h3V3a1 1 0 0 1 2 0m-4 7v10h14V10Z");
}

</style>
