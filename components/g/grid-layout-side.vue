<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mkic7mine"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:grid-layout-side" /></template>
<style>
.mkic7mine {
  fill: currentColor;
  d: path("M21 21V3zM5 21h8V3H5q-.825 0-1.412.588T3 5v14q0 .825.588 1.413T5 21m16-2V5q0-.825-.587-1.412T19 3h-4v18h4q.825 0 1.413-.587T21 19");
}

</style>
