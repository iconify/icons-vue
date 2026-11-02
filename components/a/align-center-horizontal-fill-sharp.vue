<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k3-tx8bkj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:align-center-horizontal-fill-sharp" /></template>
<style>
.k3-tx8bkj {
  fill: currentColor;
  d: path("M13 3v18a1 1 0 0 1-2 0V3a1 1 0 0 1 2 0M9 3v8H4a1 1 0 0 1-1-1V4a1 1 0 0 1 1-1Zm6 0h5a1 1 0 0 1 1 1v6a1 1 0 0 1-1 1h-5ZM9 21H6a1 1 0 0 1-1-1v-6a1 1 0 0 1 1-1h3Zm6 0v-8h3a1 1 0 0 1 1 1v6a1 1 0 0 1-1 1Z");
}

</style>
