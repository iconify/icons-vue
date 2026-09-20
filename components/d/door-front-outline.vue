<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e_mqk8vaq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:door-front-outline" /></template>
<style>
.e_mqk8vaq {
  fill: currentColor;
  d: path("M3 21v-2h2V5q0-.825.588-1.412T7 3h10q.825 0 1.413.588T19 5v14h2v2zm14-2V5H7v14zm-3-6q.425 0 .713-.288T15 12t-.288-.712T14 11t-.712.288T13 12t.288.713T14 13M7 5v14z");
}

</style>
