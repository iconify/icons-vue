<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="alsx4nw9m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:arrow-badge-right-fill-sharp" /></template>
<style>
.alsx4nw9m {
  fill: currentColor;
  d: path("M4 20a1.002 1.002 0 0 1-.707-1.707L9.586 12L3.293 5.707A1 1 0 0 1 4 4h9c.265 0 .52.105.707.293l7 7a1 1 0 0 1 0 1.414l-7 7A1 1 0 0 1 13 20Z");
}

</style>
