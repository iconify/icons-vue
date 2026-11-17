<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iq1z1-b3f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:house-alt-1-fill-round" /></template>
<style>
.iq1z1-b3f {
  fill: currentColor;
  d: path("M11 17v1a4 4 0 0 1-8 0v-6.185a5 5 0 0 1 1.707-3.763l4-3.5a5 5 0 0 1 6.586 0l4 3.5A5 5 0 0 1 21 11.815V18a4 4 0 0 1-8 0v-1a1 1 0 0 0-2 0");
}

</style>
