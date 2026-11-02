<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lg6e5mbzo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:arrow-u-turn-left-up-bulk-sharp" /></template>
<style>
.lg6e5mbzo {
  fill: currentColor;
  d: path("M10 5.414V20h8v-9a1 1 0 0 1 2 0v10a1 1 0 0 1-1 1H9a1 1 0 0 1-1-1V5.414L5.707 7.707a.999.999 0 1 1-1.414-1.414l4-4a1 1 0 0 1 1.414 0l4 4a.999.999 0 1 1-1.414 1.414Z");
}

</style>
