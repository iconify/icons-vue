<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xdif4bjbp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:arrow-up-from-line-fill-sharp" /></template>
<style>
.xdif4bjbp {
  fill: currentColor;
  d: path("M15.293 8.707L13 6.414V16a1 1 0 0 1-2 0V6.414L8.707 8.707a.999.999 0 1 1-1.414-1.414l4-4a1 1 0 0 1 1.414 0l4 4a.999.999 0 1 1-1.414 1.414M18 19a1 1 0 0 1 0 2H6a1 1 0 0 1 0-2Z");
}

</style>
