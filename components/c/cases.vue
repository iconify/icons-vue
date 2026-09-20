<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oykh-k-7t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:cases" /></template>
<style>
.oykh-k-7t {
  fill: currentColor;
  d: path("M3 22q-.825 0-1.412-.587T1 20V9h2v11h17v2zm4-4q-.825 0-1.412-.587T5 16V5h5V3q0-.825.588-1.412T12 1h4q.825 0 1.413.588T18 3v2h5v11q0 .825-.587 1.413T21 18zm5-13h4V3h-4z");
}

</style>
