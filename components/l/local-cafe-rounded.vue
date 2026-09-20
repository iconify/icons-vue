<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qqmd06t3t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:local-cafe-rounded" /></template>
<style>
.qqmd06t3t {
  fill: currentColor;
  d: path("M5 21q-.425 0-.712-.288T4 20t.288-.712T5 19h14q.425 0 .713.288T20 20t-.288.713T19 21zm3-4q-1.65 0-2.825-1.175T4 13V5q0-.825.588-1.412T6 3h14q.825 0 1.413.588T22 5v3q0 .825-.587 1.413T20 10h-2v3q0 1.65-1.175 2.825T14 17zm10-9h2V5h-2z");
}

</style>
