<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ggecmexfz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:face-smile-minus-corner-fill" /></template>
<style>
.ggecmexfz {
  fill: currentColor;
  d: path("M15 5v.01A3 3 0 0 0 18 8h2.485a1 1 0 0 1 .943.667A10 10 0 0 1 4.929 19.071a9.997 9.997 0 0 1 9.705-16.718a1.003 1.003 0 0 1 .644 1.385A3 3 0 0 0 15 5m3-1h4a1 1 0 0 1 0 2h-4a1 1 0 0 1 0-2M9 8a1 1 0 0 0 0 2h.01a1 1 0 0 0 0-2Zm6.01 0H15a1 1 0 0 0 0 2h.01a1 1 0 0 0 0-2m-6.303 5.293a.999.999 0 1 0-1.414 1.414a6.653 6.653 0 0 0 9.414 0a1.002 1.002 0 0 0-1.414-1.414a4.656 4.656 0 0 1-6.586 0");
}

</style>
