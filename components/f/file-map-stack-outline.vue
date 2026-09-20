<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ga_j9nb4z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:file-map-stack-outline" /></template>
<style>
.ga_j9nb4z {
  fill: currentColor;
  d: path("M8 18q-.825 0-1.412-.587T6 16V4q0-.825.588-1.412T8 2h12q.825 0 1.413.588T22 4v12q0 .825-.587 1.413T20 18zm0-2h12V4H8zm-4 6q-.825 0-1.412-.587T2 20V6h2v14h14v2zM8 4v12zm5.288 5.713Q13 9.425 13 9t.288-.712T14 8t.713.288T15 9t-.288.713T14 10t-.712-.288M14 15q2.025-1.725 3.013-3.187T18 9.1q0-1.875-1.213-2.988T14 5t-2.787 1.113T10 9.1q0 1.25.988 2.713T14 15");
}

</style>
