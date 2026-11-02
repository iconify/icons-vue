<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="puer1fbki"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:arrow-u-turn-left-up-fill" /></template>
<style>
.puer1fbki {
  fill: currentColor;
  d: path("M10 5.414V19a1 1 0 0 0 1 1h6a1 1 0 0 0 1-1v-8a1 1 0 0 1 2 0v8a3 3 0 0 1-3 3h-6a3 3 0 0 1-3-3V5.414L5.707 7.707a.999.999 0 1 1-1.414-1.414l4-4a1 1 0 0 1 1.414 0l4 4a.999.999 0 1 1-1.414 1.414Z");
}

</style>
