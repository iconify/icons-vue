<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ebcri32bw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:braces-fill-sharp" /></template>
<style>
.ebcri32bw {
  fill: currentColor;
  d: path("M7 8v2c0 .265-.105.52-.293.707L5.414 12l1.293 1.293A1 1 0 0 1 7 14v2h1a1 1 0 0 1 0 2H6a1 1 0 0 1-1-1v-2.586l-1.707-1.707a1 1 0 0 1 0-1.414L5 9.586V7a1 1 0 0 1 1-1h2a1 1 0 0 1 0 2Zm11-2a1 1 0 0 1 1 1v2.586l1.707 1.707a1 1 0 0 1 0 1.414L19 14.414V17a1 1 0 0 1-1 1h-2a1 1 0 0 1 0-2h1v-2c0-.265.105-.52.293-.707L18.586 12l-1.293-1.293A1 1 0 0 1 17 10V8h-1a1 1 0 0 1 0-2Z");
}

</style>
