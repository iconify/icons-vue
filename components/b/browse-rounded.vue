<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y_9c27bmf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:browse-rounded" /></template>
<style>
.y_9c27bmf {
  fill: currentColor;
  d: path("M3 13V5q0-.825.588-1.412T5 3h6v10zM13 3h6q.825 0 1.413.588T21 5v4h-8zm0 18V11h8v8q0 .825-.587 1.413T19 21zM3 15h8v6H5q-.825 0-1.412-.587T3 19z");
}

</style>
