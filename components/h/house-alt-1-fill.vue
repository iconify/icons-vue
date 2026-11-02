<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w-8gk3bps"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:house-alt-1-fill" /></template>
<style>
.w-8gk3bps {
  fill: currentColor;
  d: path("M11 17v2a3 3 0 0 1-3 3H6a3 3 0 0 1-3-3v-7c0-1.039.578-1.992 1.293-2.707l6-6a2.414 2.414 0 0 1 3.414 0l6 6C20.422 10.008 21 10.961 21 12v7a3 3 0 0 1-3 3h-2a3 3 0 0 1-3-3v-2a1 1 0 0 0-2 0");
}

</style>
