<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j6uld30lx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:hydrogen-fill-sharp" /></template>
<style>
.j6uld30lx {
  fill: currentColor;
  d: path("M14 2a1 1 0 0 1 0 2h-1v1.061A8.006 8.006 0 0 1 20 13v8a1 1 0 0 1-1 1H5a1 1 0 0 1-1-1v-8a8.006 8.006 0 0 1 7-7.939V4h-1a1 1 0 0 1 0-2Zm-4 13h4v2a1 1 0 0 0 2 0v-6a1 1 0 0 0-2 0v2h-4v-2a1 1 0 0 0-2 0v6a1 1 0 0 0 2 0Z");
}

</style>
