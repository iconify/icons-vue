<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p-96hmbpm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:add-road-sharp" /></template>
<style>
.p-96hmbpm {
  fill: currentColor;
  d: path("M18 23v-3h-3v-2h3v-3h2v3h3v2h-3v3zm0-10V4h2v9zM4 20V4h2v16zm7-12V4h2v4zm0 6v-4h2v4zm0 6v-4h2v4z");
}

</style>
