<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bjqda37gw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:file-open-outline-rounded" /></template>
<style>
.bjqda37gw {
  fill: currentColor;
  d: path("M6 22q-.825 0-1.412-.587T4 20V4q0-.825.588-1.412T6 2h7.175q.4 0 .763.15t.637.425l4.85 4.85q.275.275.425.638t.15.762V13q0 .425-.288.713T19 14t-.712-.288T18 13V9h-4q-.425 0-.712-.288T13 8V4H6v16h8q.425 0 .713.288T15 21t-.288.713T14 22zm13-2.575v1.225q0 .425-.288.713T18 21.65t-.712-.287T17 20.65V17q0-.425.288-.712T18 16h3.65q.425 0 .713.288t.287.712t-.287.713t-.713.287H20.4l2.25 2.25q.275.275.275.688t-.275.712q-.3.3-.712.3t-.713-.3zM6 20V4z");
}

</style>
