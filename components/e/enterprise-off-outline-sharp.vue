<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="agkrx8bmf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:enterprise-off-outline-sharp" /></template>
<style>
.agkrx8bmf {
  fill: currentColor;
  d: path("M20.5 23.3L18.2 21H4q-.825 0-1.412-.587T2 19V8q0-.825.588-1.412T4 6h2l2 2H4v11h12.175L.7 3.5l1.4-1.4l19.8 19.8zm1.5-4.15l-2-2V8h-9.15L8 5.15V4q0-.825.588-1.412T10 2h4q.825 0 1.413.588T16 4v2h4q.825 0 1.413.588T22 8zM10 6h4V4h-4zm.7 7.5");
}

</style>
