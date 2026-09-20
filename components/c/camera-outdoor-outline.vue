<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fi5bsqwvn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:camera-outdoor-outline" /></template>
<style>
.fi5bsqwvn {
  fill: currentColor;
  d: path("M13 18q-.425 0-.712-.288T12 17v-4q0-.425.288-.712T13 12h4q.425 0 .713.288T18 13v1l2-1.05v4.1L18 16v1q0 .425-.288.713T17 18zm-9 3V9l8-6l8 6v2h-2v-1l-6-4.5L6 10v9h14v2zm8-8.75");
}

</style>
