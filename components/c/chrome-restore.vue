<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zibj73l9r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:chrome-restore" /></template>
<style>
.zibj73l9r {
  fill: currentColor;
  d: path("M10 16q-.825 0-1.413-.588T8 14V6q0-.825.588-1.413T10 4h8q.825 0 1.413.588T20 6v8q0 .825-.588 1.413T18 16h-8Zm-4 4q-.825 0-1.413-.588T4 18V8.525h2V18h9.475v2H6Z");
}

</style>
