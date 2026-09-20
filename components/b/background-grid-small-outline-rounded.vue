<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wrw2r6b-i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:background-grid-small-outline-rounded" /></template>
<style>
.wrw2r6b-i {
  fill: currentColor;
  d: path("M5 19h2v-2H5zm4 0h2v-2H9zm4 0h2v-2h-2zm4 0h2v-2h-2zM5 7h2V5H5zm0 4h2V9H5zm0 4h2v-2H5zm4-8h2V5H9zm0 4h2V9H9zm0 4h2v-2H9zm4-8h2V5h-2zm0 4h2V9h-2zm0 4h2v-2h-2zm4-8h2V5h-2zm0 4h2V9h-2zm0 4h2v-2h-2zM5 21q-.825 0-1.412-.587T3 19V5q0-.825.588-1.412T5 3h14q.825 0 1.413.588T21 5v14q0 .825-.587 1.413T19 21z");
}

</style>
