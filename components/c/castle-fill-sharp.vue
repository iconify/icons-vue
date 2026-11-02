<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pj04a46rp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:castle-fill-sharp" /></template>
<style>
.pj04a46rp {
  fill: currentColor;
  d: path("M5 3a1 1 0 0 1 2 0v1h2V3a1 1 0 0 1 2 0v1h2V3a1 1 0 0 1 2 0v1h2V3a1 1 0 0 1 2 0v7h2a1 1 0 0 1 1 1v10a1 1 0 0 1-1 1h-5v-4a4 4 0 0 0-8 0v4H3a1 1 0 0 1-1-1V11a1 1 0 0 1 1-1h2Z");
}

</style>
