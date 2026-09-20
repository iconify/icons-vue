<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p-e6d1bbm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:game-stick-l3-rounded" /></template>
<style>
.p-e6d1bbm {
  fill: currentColor;
  d: path("M12 5L9 1h6zm5 12.35V20q0 .825-.587 1.413T15 22H9q-.825 0-1.412-.587T7 20v-2.65q-2.275-.8-3.637-2.187T2 12.075q0-2.525 2.913-4.3T12 6t7.088 1.775t2.912 4.3q0 1.7-1.362 3.088T17 17.35m-5.725-2.85h2.275q.2 0 .325-.125T14 14.05t-.125-.325t-.325-.125h-1.775V10q0-.2-.15-.35t-.35-.15t-.35.15t-.15.35v4q0 .2.15.35t.35.15");
}

</style>
