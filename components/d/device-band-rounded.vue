<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ob79izbzi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:device-band-rounded" /></template>
<style>
.ob79izbzi {
  fill: currentColor;
  d: path("M10 22q-.825 0-1.412-.587T8 20V9q-.425 0-.712-.288T7 8V7q0-.425.288-.712T8 6V4q0-.825.588-1.412T10 2h4q.825 0 1.413.588T16 4v2q.425 0 .713.288T17 7v1q0 .425-.288.713T16 9v11q0 .825-.587 1.413T14 22z");
}

</style>
