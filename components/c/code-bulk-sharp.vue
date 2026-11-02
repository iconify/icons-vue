<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r7du0phez"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:code-bulk-sharp" /></template>
<style>
.r7du0phez {
  fill: currentColor;
  d: path("M3.293 12.707a1 1 0 0 1 0-1.414l5-5a.999.999 0 1 1 1.414 1.414L5.414 12l4.293 4.293a.999.999 0 1 1-1.414 1.414Zm17.414-1.414a1 1 0 0 1 0 1.414l-5 5a.999.999 0 1 1-1.414-1.414L18.586 12l-4.293-4.293a.999.999 0 1 1 1.414-1.414Z");
}

</style>
