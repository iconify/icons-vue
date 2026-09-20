<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bwmaeeb4m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:gradient-outline" /></template>
<style>
.bwmaeeb4m {
  fill: currentColor;
  d: path("M11 13v-2h2v2zm-2 2v-2h2v2zm4 0v-2h2v2zm2-2v-2h2v2zm-8 0v-2h2v2zm-2 8q-.825 0-1.412-.587T3 19V5q0-.825.588-1.412T5 3h14q.825 0 1.413.588T21 5v14q0 .825-.587 1.413T19 21zm2-2h2v-2H7zm4 0h2v-2h-2zm8 0v-2zM5 17h2v-2h2v2h2v-2h2v2h2v-2h2v2h2v-2h-2v-2h2V5H5v8h2v2H5zm0 2V5zm14-6v2zm-4 4v2h2v-2z");
}

</style>
