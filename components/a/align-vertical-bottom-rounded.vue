<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fwlqi7-vl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:align-vertical-bottom-rounded" /></template>
<style>
.fwlqi7-vl {
  fill: currentColor;
  d: path("M3 22q-.425 0-.712-.288T2 21t.288-.712T3 20h18q.425 0 .713.288T22 21t-.288.713T21 22zm4.438-4.437Q7 17.125 7 16.5v-13q0-.625.438-1.062T8.5 2t1.063.438T10 3.5v13q0 .625-.437 1.063T8.5 18t-1.062-.437m7 0Q14 17.125 14 16.5v-7q0-.625.438-1.062T15.5 8t1.063.438T17 9.5v7q0 .625-.437 1.063T15.5 18t-1.062-.437");
}

</style>
