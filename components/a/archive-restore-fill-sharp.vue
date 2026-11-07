<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kgjysu-0j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:archive-restore-fill-sharp" /></template>
<style>
.kgjysu-0j {
  fill: currentColor;
  d: path("M2 8V4a1 1 0 0 1 1-1h18a1 1 0 0 1 1 1v4a1 1 0 0 1-1 1h-1v11a1 1 0 0 1-1 1H5a1 1 0 0 1-1-1V9H3a1 1 0 0 1-1-1m4 1v10h12V9Zm5 4.414l-1.293 1.293a.999.999 0 1 1-1.414-1.414l3-3a1 1 0 0 1 1.414 0l3 3a.999.999 0 1 1-1.414 1.414L13 13.414V17a1 1 0 0 1-2 0Z");
}

</style>
