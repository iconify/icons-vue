<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u1209kh4y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:blinds-2-rounded" /></template>
<style>
.u1209kh4y {
  fill: currentColor;
  d: path("M6.596 21q-.666 0-1.14-.475t-.475-1.14V7.769H3.808q-.343 0-.576-.232T3 6.962V5.377q0-.99.696-1.684T5.385 3h13.23q.981 0 1.683.702T21 5.388v1.574q0 .343-.232.575t-.576.232H19v11.616q0 .666-.475 1.14t-1.14.475zm0-1h10.789q.269 0 .442-.173t.173-.442v-3.097H5.98v3.096q0 .27.174.443q.173.173.442.173m-.615-4.712H18v-3.73h-2.788v1.384q0 .213-.144.357t-.356.143q-.195 0-.347-.143q-.153-.144-.153-.357v-1.384H5.98zm0-4.73h8.23V7.769h-8.23zm9.23 0H18V7.769h-2.788z");
}

</style>
