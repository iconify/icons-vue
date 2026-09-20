<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fmw7d_b6l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:image-inset" /></template>
<style>
.fmw7d_b6l {
  fill: currentColor;
  d: path("M6 16h12V8H6zm-2 4q-.825 0-1.412-.587T2 18V6q0-.825.588-1.412T4 4h16q.825 0 1.413.588T22 6v12q0 .825-.587 1.413T20 20zm4-6l2.125-2.825L11.5 13l1.875-2.5L16 14z");
}

</style>
