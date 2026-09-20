<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zwqzt3buj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:flag-outline-rounded" /></template>
<style>
.zwqzt3buj {
  fill: currentColor;
  d: path("M7 14v6q0 .425-.288.713T6 21t-.712-.288T5 20V5q0-.425.288-.712T6 4h7.175q.35 0 .625.225t.35.575L14.4 6H19q.425 0 .713.288T20 7v8q0 .425-.288.713T19 16h-5.175q-.35 0-.625-.225t-.35-.575L12.6 14zm7.65 0H18V8h-4.425q-.35 0-.625-.225T12.6 7.2L12.35 6H7v6h6.425q.35 0 .625.225t.35.575zm-2.15-4");
}

</style>
