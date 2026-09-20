<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="unpu4x64x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:event-seat-outline" /></template>
<style>
.unpu4x64x {
  fill: currentColor;
  d: path("M4 21v-6h16v6h-2v-4H6v4zm.5-7q-.625 0-1.062-.437T3 12.5t.438-1.062T4.5 11t1.063.438T6 12.5t-.437 1.063T4.5 14M7 14V5q0-.825.588-1.412T9 3h6q.825 0 1.413.588T17 5v9zm11.438-.437Q18 13.125 18 12.5t.438-1.062T19.5 11t1.063.438T21 12.5t-.437 1.063T19.5 14t-1.062-.437M9 12h6V5H9zm0 0h6z");
}

</style>
