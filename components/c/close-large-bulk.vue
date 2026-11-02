<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x0u_55gvt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:close-large-bulk" /></template>
<style>
.x0u_55gvt {
  fill: currentColor;
  d: path("m12 10.586l8.293-8.293a.999.999 0 1 1 1.414 1.414L13.414 12l8.293 8.293a.999.999 0 1 1-1.414 1.414L12 13.414l-8.293 8.293a.999.999 0 1 1-1.414-1.414L10.586 12L2.293 3.707a.999.999 0 1 1 1.414-1.414Z");
}

</style>
