<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n6hchxmzx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:chart-area-fill-sharp" /></template>
<style>
.n6hchxmzx {
  fill: currentColor;
  d: path("M4 19h17a1 1 0 0 1 0 2H3a1 1 0 0 1-1-1V4a1 1 0 0 1 2 0Zm2-3v-4c0-.265.105-.52.293-.707l3-3a1 1 0 0 1 1.414 0L13 10.586l5.293-5.293A1 1 0 0 1 20 6v10a1 1 0 0 1-1 1H7a1 1 0 0 1-1-1");
}

</style>
