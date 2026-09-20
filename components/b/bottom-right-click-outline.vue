<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y8uw43bzt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:bottom-right-click-outline" /></template>
<style>
.y8uw43bzt {
  fill: currentColor;
  d: path("M3 21v-2h16V3h2v16q0 .825-.587 1.413T19 21zm10.588-4.587Q13 15.825 13 15t.588-1.412T15 13t1.413.588T17 15t-.587 1.413T15 17t-1.412-.587M5 12v-2h3.6L3 4.4L4.4 3L10 8.6V5h2v7z");
}

</style>
