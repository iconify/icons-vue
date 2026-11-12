<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j5n1k8cke"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:boolean-exclude-fill-round" /></template>
<style>
.j5n1k8cke {
  fill: currentColor;
  d: path("M9 9v5l-2 2H5a3 3 0 0 1-3-3V5a3 3 0 0 1 3-3h8a3 3 0 0 1 3 3v2l-2 2Zm-1 8l2-2h5v-5l2-2h2a3 3 0 0 1 3 3v8a3 3 0 0 1-3 3h-8a3 3 0 0 1-3-3Z");
}

</style>
