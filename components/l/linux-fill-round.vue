<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f3dt1wbnv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:linux-fill-round" /></template>
<style>
.f3dt1wbnv {
  fill: currentColor;
  d: path("M21 22h-4v-1c0-2.563-2.448-4.999-5-5c-2.552.001-5 2.437-5 5v1H3a1 1 0 0 1-.894-1.447c.172-.345.355-.685.537-1.025c.278-.518.554-1.036.811-1.564q.426-.867.762-1.772C4.707 14.85 5 13.432 5 12V9a7 7 0 1 1 14 0v3c0 1.432.293 2.85.784 4.192q.336.906.762 1.772c.257.528.533 1.046.811 1.564c.182.34.365.68.537 1.025a.997.997 0 0 1-.447 1.341A1 1 0 0 1 21 22M10.01 8H10a1 1 0 0 0 0 2h.01a1 1 0 0 0 0-2m4 0H14a1 1 0 0 0 0 2h.01a1 1 0 0 0 0-2M14 11h-4a1.002 1.002 0 0 0-.707 1.707l2 2a1 1 0 0 0 1.414 0l2-2A1 1 0 0 0 14 11m1 10v1H9v-1c0-.768.428-1.514.957-2.043C10.492 18.422 11.226 18 12 18c1.423 0 3 1.525 3 3");
}

</style>
