<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w4gc1qb8n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:add-photo-alternate-outline" /></template>
<style>
.w4gc1qb8n {
  fill: currentColor;
  d: path("M5 21q-.825 0-1.412-.587T3 19V5q0-.825.588-1.412T5 3h8v2H5v14h14v-8h2v8q0 .825-.587 1.413T19 21zm1-4h12l-3.75-5l-3 4L9 13zm11-8V7h-2V5h2V3h2v2h2v2h-2v2z");
}

</style>
