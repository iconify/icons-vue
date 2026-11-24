<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vtzihrb7i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:download-fill-sharp" /></template>
<style>
.vtzihrb7i {
  fill: currentColor;
  d: path("M7.293 12.707a.999.999 0 1 1 1.414-1.414L11 13.586V4a1 1 0 0 1 2 0v9.586l2.293-2.293a.999.999 0 1 1 1.414 1.414l-4 4a1 1 0 0 1-1.414 0ZM5 16v3h14v-3a1 1 0 0 1 2 0v4a1 1 0 0 1-1 1H4a1 1 0 0 1-1-1v-4a1 1 0 0 1 2 0");
}

</style>
