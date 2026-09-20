<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a_077_d8z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:hallway" /></template>
<style>
.a_077_d8z {
  fill: currentColor;
  d: path("M5 22q-.825 0-1.412-.587T3 20V6q0-.825.588-1.412T5 4h3l4-4l4 4h3q.825 0 1.413.588T21 6v14q0 .825-.587 1.413T19 22zm1-4h12l-3.75-5l-3 4L9 14zm4.1-14h3.8L12 2.1z");
}

</style>
