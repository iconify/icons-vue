<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="akj8vpb2z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:arrow-left-small-bulk-round" /></template>
<style>
.akj8vpb2z {
  fill: currentColor;
  d: path("M9.414 11H17a1 1 0 0 1 0 2H9.414l2.293 2.293a.999.999 0 1 1-1.414 1.414l-4-4a.997.997 0 0 1 0-1.414l4-4a.999.999 0 1 1 1.414 1.414Z");
}

</style>
