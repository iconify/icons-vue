<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rptoojz2b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:arrow-up-bulk" /></template>
<style>
.rptoojz2b {
  fill: currentColor;
  d: path("M13 7.414V19a1 1 0 0 1-2 0V7.414l-3.293 3.293a.999.999 0 1 1-1.414-1.414l5-5a1 1 0 0 1 1.414 0l5 5a.999.999 0 1 1-1.414 1.414Z");
}

</style>
