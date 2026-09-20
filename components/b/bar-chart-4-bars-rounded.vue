<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xyald3ods"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:bar-chart-4-bars-rounded" /></template>
<style>
.xyald3ods {
  fill: currentColor;
  d: path("M3 21q-.425 0-.712-.288T2 20t.288-.712T3 19h18q.425 0 .713.288T22 20t-.288.713T21 21zm.438-3.437Q3 17.125 3 16.5v-4q0-.625.438-1.062T4.5 11t1.063.438T6 12.5v4q0 .625-.437 1.063T4.5 18t-1.062-.437m5 0Q8 17.125 8 16.5v-9q0-.625.438-1.062T9.5 6t1.063.438T11 7.5v9q0 .625-.437 1.063T9.5 18t-1.062-.437m5 0Q13 17.125 13 16.5v-6q0-.625.438-1.062T14.5 9t1.063.438T16 10.5v6q0 .625-.437 1.063T14.5 18t-1.062-.437m5 0Q18 17.125 18 16.5v-12q0-.625.438-1.062T19.5 3t1.063.438T21 4.5v12q0 .625-.437 1.063T19.5 18t-1.062-.437");
}

</style>
