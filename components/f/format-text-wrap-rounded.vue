<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="klfx9zbhu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:format-text-wrap-rounded" /></template>
<style>
.klfx9zbhu {
  fill: currentColor;
  d: path("M4.288 19.713Q4 19.425 4 19V5q0-.425.288-.712T5 4t.713.288T6 5v14q0 .425-.288.713T5 20t-.712-.288m14 0Q18 19.426 18 19V5q0-.425.288-.712T19 4t.713.288T20 5v14q0 .425-.288.713T19 20t-.712-.288m-8.413-2.887L7.75 14.7q-.3-.3-.3-.7t.3-.7l2.15-2.125q.275-.275.688-.288t.712.288q.275.275.275.7t-.275.7l-.425.425H13q.825 0 1.413-.587T15 11t-.587-1.412T13 9H8q-.425 0-.712-.288T7 8t.288-.712T8 7h5q1.65 0 2.825 1.175T17 11t-1.175 2.825T13 15h-2.125l.425.425q.275.275.275.688t-.275.712q-.3.3-.712.3t-.713-.3");
}

</style>
