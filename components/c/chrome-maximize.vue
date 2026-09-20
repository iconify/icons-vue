<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n8hgg1b5s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:chrome-maximize" /></template>
<style>
.n8hgg1b5s {
  fill: currentColor;
  d: path("M6 20q-.825 0-1.413-.588T4 18V6q0-.825.588-1.413T6 4h12q.825 0 1.413.588T20 6v12q0 .825-.588 1.413T18 20H6Z");
}

</style>
