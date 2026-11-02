<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yie9aac_c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:brackets-fill-sharp" /></template>
<style>
.yie9aac_c {
  fill: currentColor;
  d: path("M5 8v8h2a1 1 0 0 1 0 2H4a1 1 0 0 1-1-1V7a1 1 0 0 1 1-1h3a1 1 0 0 1 0 2Zm15-2a1 1 0 0 1 1 1v10a1 1 0 0 1-1 1h-3a1 1 0 0 1 0-2h2V8h-2a1 1 0 0 1 0-2Z");
}

</style>
