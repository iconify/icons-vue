<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kg47wob0l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:hallway-outline-rounded" /></template>
<style>
.kg47wob0l {
  fill: currentColor;
  d: path("M5 22q-.825 0-1.412-.587T3 20V6q0-.825.588-1.412T5 4h3L11.3.7q.3-.3.7-.3t.7.3L16 4h3q.825 0 1.413.588T21 6v14q0 .825-.587 1.413T19 22zm0-2h14V6H5zm6.25-3L9.4 14.525q-.15-.2-.4-.2t-.4.2l-2 2.675q-.2.25-.05.525T7 18h10q.3 0 .45-.275t-.05-.525l-2.75-3.675q-.15-.2-.4-.2t-.4.2zM10.1 4h3.8L12 2.1zM5 20V6z");
}

</style>
