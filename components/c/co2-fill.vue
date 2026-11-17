<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kxkrek6kf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:co2-fill" /></template>
<style>
.kxkrek6kf {
  fill: currentColor;
  d: path("M4 7v6h2a1 1 0 0 1 0 2H4a2 2 0 0 1-2-2V7a2 2 0 0 1 2-2h2a1 1 0 0 1 0 2Zm7 8a2 2 0 0 1-2-2V7a2 2 0 0 1 2-2h2a2 2 0 0 1 2 2v6a2 2 0 0 1-2 2Zm1-8h-1v6h2V7Zm8 4a2 2 0 0 1 2 2v1a2 2 0 0 1-2 2h-1v1h2a1 1 0 0 1 0 2h-2a2 2 0 0 1-2-2v-1a2 2 0 0 1 2-2h1v-1h-2a1 1 0 0 1 0-2Z");
}

</style>
