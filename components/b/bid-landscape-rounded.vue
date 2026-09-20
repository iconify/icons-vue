<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oeah8vxhu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:bid-landscape-rounded" /></template>
<style>
.oeah8vxhu {
  fill: currentColor;
  d: path("M5 21q-.825 0-1.412-.587T3 19V5q0-.825.588-1.412T5 3h14q.825 0 1.413.588T21 5v14q0 .825-.587 1.413T19 21zM19 7.25l-6.05 6.8L9.7 10.8q-.3-.3-.7-.3t-.7.3L5 14.1v2.85l4-4l3.3 3.3q.3.3.738.288t.712-.338L19 10.25z");
}

</style>
