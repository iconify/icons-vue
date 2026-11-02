<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ricnnkb6w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:battery-empty-fill-sharp" /></template>
<style>
.ricnnkb6w {
  fill: currentColor;
  d: path("M2 17V7a1 1 0 0 1 1-1h15a1 1 0 0 1 1 1v10a1 1 0 0 1-1 1H3a1 1 0 0 1-1-1m20-3a1 1 0 0 1-2 0v-4a1 1 0 0 1 2 0Z");
}

</style>
