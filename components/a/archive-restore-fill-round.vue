<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c7h66ghub"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:archive-restore-fill-round" /></template>
<style>
.c7h66ghub {
  fill: currentColor;
  d: path("M5 3h14a3 3 0 0 1 1 5.829V16a5 5 0 0 1-1.464 3.536A5 5 0 0 1 15 21H9a5 5 0 0 1-5-5V8.829A3.001 3.001 0 0 1 5 3m1 6v7a3 3 0 0 0 3 3h6a3 3 0 0 0 3-3V9Zm5 4.414l-1.293 1.293a.999.999 0 1 1-1.414-1.414l3-3a1 1 0 0 1 1.414 0l3 3a.999.999 0 1 1-1.414 1.414L13 13.414V17a1 1 0 0 1-2 0Z");
}

</style>
