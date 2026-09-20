<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m9-lqybvz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:document-scanner" /></template>
<style>
.m9-lqybvz {
  fill: currentColor;
  d: path("M2 6V1h5v2H4v3zm18 0V3h-3V1h5v5zM2 23v-5h2v3h3v2zm15 0v-2h3v-3h2v5zM7 20q-.825 0-1.412-.587T5 18V6q0-.825.588-1.412T7 4h10q.825 0 1.413.588T19 6v12q0 .825-.587 1.413T17 20zm2-10h6V8H9zm0 3h6v-2H9zm0 3h6v-2H9z");
}

</style>
