<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h2zgr4bei"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:computer-arrow-up-sharp" /></template>
<style>
.h2zgr4bei {
  fill: currentColor;
  d: path("M11 14.5h2v-4.175l1.6 1.575l1.4-1.4l-4-4l-4 4l1.4 1.425l1.6-1.6zM1 21v-2h22v2zm1-3V3h20v15z");
}

</style>
