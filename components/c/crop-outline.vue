<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nfkf7qrnl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:crop-outline" /></template>
<style>
.nfkf7qrnl {
  fill: currentColor;
  d: path("M17 23v-4H7q-.825 0-1.412-.587T5 17V7H1V5h4V1h2v16h16v2h-4v4zm0-8V7H9V5h8q.825 0 1.413.588T19 7v8z");
}

</style>
