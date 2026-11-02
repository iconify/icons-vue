<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mnrvyhb3o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:aspect-ratio-fill" /></template>
<style>
.mnrvyhb3o {
  fill: currentColor;
  d: path("M2 7a3 3 0 0 1 3-3h14a3 3 0 0 1 3 3v10a3 3 0 0 1-3 3H5a3 3 0 0 1-3-3Zm4 5a1 1 0 0 0 2 0v-2h2a1 1 0 0 0 0-2H8a2 2 0 0 0-2 2Zm12 2v-2a1 1 0 0 0-2 0v2h-2a1 1 0 0 0 0 2h2a2 2 0 0 0 2-2");
}

</style>
