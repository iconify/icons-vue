<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dgn_oh1gn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:jamboard-kiosk" /></template>
<style>
.dgn_oh1gn {
  fill: currentColor;
  d: path("M6 21v-2h5v-3H4q-.825 0-1.412-.587T2 14V5q0-.825.588-1.412T4 3h16q.825 0 1.413.588T22 5v9q0 .825-.587 1.413T20 16h-7v3h5v2z");
}

</style>
