<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gson9vbgm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:arrow-big-left-fill-sharp" /></template>
<style>
.gson9vbgm {
  fill: currentColor;
  d: path("M21 9v6a1 1 0 0 1-1 1h-7v4a1.002 1.002 0 0 1-1.707.707l-8-8a1 1 0 0 1 0-1.414l8-8A1 1 0 0 1 13 4v4h7a1 1 0 0 1 1 1");
}

</style>
