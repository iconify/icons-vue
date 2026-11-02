<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qbf-hnbrg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:chart-area-fill-round" /></template>
<style>
.qbf-hnbrg {
  fill: currentColor;
  d: path("M4 16a3 3 0 0 0 3 3h14a1 1 0 0 1 0 2H7a5 5 0 0 1-5-5V4a1 1 0 0 1 2 0Zm2-2v-1c0-1.039.578-1.992 1.293-2.707l1-1a2.414 2.414 0 0 1 3.414 0l1 1a.414.414 0 0 0 .586 0l4-4c.31-.311.752-.456 1.186-.382C19.428 6.072 20 7.102 20 8v6a3 3 0 0 1-3 3H9a3 3 0 0 1-3-3");
}

</style>
