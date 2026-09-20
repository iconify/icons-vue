<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pxde7lbyh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:collections-bookmark-outline" /></template>
<style>
.pxde7lbyh {
  fill: currentColor;
  d: path("M8 16h12V4h-2v7l-2.5-1.5L13 11V4H8zm0 2q-.825 0-1.412-.587T6 16V4q0-.825.588-1.412T8 2h12q.825 0 1.413.588T22 4v12q0 .825-.587 1.413T20 18zm-4 4q-.825 0-1.412-.587T2 20V6h2v14h14v2zm9-18h5zM8 4h12z");
}

</style>
