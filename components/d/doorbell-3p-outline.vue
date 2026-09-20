<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qhtyvd3ao"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:doorbell-3p-outline" /></template>
<style>
.qhtyvd3ao {
  fill: currentColor;
  d: path("M7.616 21q-.667 0-1.141-.475T6 19.386V4.615q0-.666.475-1.14T7.615 3h8.77q.666 0 1.14.475T18 4.615v14.77q0 .666-.475 1.14t-1.14.475zm0-1h8.769q.269 0 .442-.173t.173-.442V4.615q0-.269-.173-.442T16.385 4h-8.77q-.269 0-.442.173T7 4.616v14.769q0 .269.173.442t.443.173M12 18.5q.778 0 1.331-.553q.554-.554.554-1.331q0-.778-.554-1.331q-.553-.554-1.331-.554t-1.331.554t-.553 1.33t.553 1.332T12 18.5m0-.77q-.463 0-.79-.325t-.326-.79t.326-.789t.79-.326t.79.326t.326.79t-.326.789t-.79.326m.61-4.772q.236-.232.236-.613h-1.692q0 .373.237.61q.236.236.609.236t.61-.233m-3.994-1.113h6.769v-.769h-.846V9.125q0-.954-.48-1.697q-.478-.744-1.38-1.002v-.259q0-.302-.193-.496T12 5.477t-.486.193t-.193.492v.257q-.902.322-1.38 1.04q-.48.72-.48 1.672v1.946h-.845zM7 20V4z");
}

</style>
