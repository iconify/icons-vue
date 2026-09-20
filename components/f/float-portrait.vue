<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="on5iiabgj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:float-portrait" /></template>
<style>
.on5iiabgj {
  fill: currentColor;
  d: path("M15 22v-7h5v7h-5Zm-9 0q-.825 0-1.413-.588T4 20V4q0-.825.588-1.413T6 2h12q.825 0 1.413.588T20 4v9h-7v9H6Z");
}

</style>
