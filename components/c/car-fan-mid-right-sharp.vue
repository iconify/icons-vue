<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c20kuyt6i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:car-fan-mid-right-sharp" /></template>
<style>
.c20kuyt6i {
  fill: currentColor;
  d: path("M10.725 23L9 22l4.025-7H16.5l1.45-5.025q.25-.875.925-1.425T20.4 8q1.2 0 1.963.912t.537 2.113L21.5 18h-7.875zM21 7q-.825 0-1.412-.587T19 5t.588-1.412T21 3t1.413.588T23 5t-.587 1.413T21 7M7 12l-1.4-1.4L8.175 8H2V6h6.175l-2.6-2.6L7 2l5 5z");
}

</style>
