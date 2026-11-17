<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z9g6kb5af"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:house-alt-2-fill" /></template>
<style>
.z9g6kb5af {
  fill: currentColor;
  d: path("M3 22a1 1 0 0 1 0-2v-9.092c0-.866.373-1.689 1.024-2.258l6-5.25a3 3 0 0 1 3.952 0l6 5.25A3 3 0 0 1 21 10.908V20a1 1 0 0 1 0 2Zm11-5a2 2 0 1 0-4 0v3h4Z");
}

</style>
