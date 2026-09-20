<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hwg1b2bwi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:left-panel-open-outline" /></template>
<style>
.hwg1b2bwi {
  fill: currentColor;
  d: path("M12.5 8v8l4-4zM5 21q-.825 0-1.412-.587T3 19V5q0-.825.588-1.412T5 3h14q.825 0 1.413.588T21 5v14q0 .825-.587 1.413T19 21zm3-2V5H5v14zm2 0h9V5h-9zm-2 0H5z");
}

</style>
