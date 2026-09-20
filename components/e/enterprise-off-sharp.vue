<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="niaq5ljpm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:enterprise-off-sharp" /></template>
<style>
.niaq5ljpm {
  fill: currentColor;
  d: path("m22 19.15l-14-14V4q0-.825.588-1.412T10 2h4q.825 0 1.413.588T16 4v2h4q.825 0 1.413.588T22 8zM10 6h4V4h-4zm10.5 17.3L18.2 21H4q-.825 0-1.412-.587T2 19V8q0-.825.588-1.412T4 6h2v2.8L.7 3.5l1.4-1.4l19.8 19.8z");
}

</style>
