<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dwhdmjb6m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:casino-outline-sharp" /></template>
<style>
.dwhdmjb6m {
  fill: currentColor;
  d: path("M8.563 17.563Q9 17.125 9 16.5t-.437-1.062T7.5 15t-1.062.438T6 16.5t.438 1.063T7.5 18t1.063-.437m0-9Q9 8.124 9 7.5t-.437-1.062T7.5 6t-1.062.438T6 7.5t.438 1.063T7.5 9t1.063-.437m4.5 4.5q.437-.438.437-1.063t-.437-1.062T12 10.5t-1.062.438T10.5 12t.438 1.063T12 13.5t1.063-.437m4.5 4.5Q18 17.125 18 16.5t-.437-1.062T16.5 15t-1.062.438T15 16.5t.438 1.063T16.5 18t1.063-.437m0-9Q18 8.124 18 7.5t-.437-1.062T16.5 6t-1.062.438T15 7.5t.438 1.063T16.5 9t1.063-.437M3 21V3h18v18zm2-2h14V5H5zm0 0V5z");
}

</style>
