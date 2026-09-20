<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i8tvbacsy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:crop-5-4-outline-rounded" /></template>
<style>
.i8tvbacsy {
  fill: currentColor;
  d: path("M5 20q-.825 0-1.412-.587T3 18V6q0-.825.588-1.412T5 4h14q.825 0 1.413.588T21 6v12q0 .825-.587 1.413T19 20zm0-2h14V6H5zm0 0V6z");
}

</style>
