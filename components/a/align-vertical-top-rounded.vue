<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d7-a7nbto"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:align-vertical-top-rounded" /></template>
<style>
.d7-a7nbto {
  fill: currentColor;
  d: path("M7.438 21.563Q7 21.125 7 20.5v-13q0-.625.438-1.062T8.5 6t1.063.438T10 7.5v13q0 .625-.437 1.063T8.5 22t-1.062-.437m7-6Q14 15.125 14 14.5v-7q0-.625.438-1.062T15.5 6t1.063.438T17 7.5v7q0 .625-.437 1.063T15.5 16t-1.062-.437M3 4q-.425 0-.712-.288T2 3t.288-.712T3 2h18q.425 0 .713.288T22 3t-.288.713T21 4z");
}

</style>
