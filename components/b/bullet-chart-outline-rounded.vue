<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tosmjtl5r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:bullet-chart-outline-rounded" /></template>
<style>
.tosmjtl5r {
  fill: currentColor;
  d: path("M11.5 18.135H4.616q-.667 0-1.141-.475T3 16.52V7.5q0-.666.475-1.14q.474-.476 1.14-.476H11.5V4.5q0-.213.144-.356T12.001 4t.356.144t.143.356v1.385h6.885q.666 0 1.14.474Q21 6.834 21 7.5v9.02q0 .666-.475 1.14t-1.14.475H12.5V19.5q0 .213-.144.356t-.357.144t-.356-.144t-.143-.356zm0-1v-2.75H4v2.134q0 .27.173.443t.443.173zM4 9.635h7.5v-2.75H4.616q-.27 0-.443.173T4 7.5zm0 3.75h9.712q.269 0 .442-.174q.173-.173.173-.442V11.25q0-.27-.173-.442q-.173-.173-.442-.173H4zm8.5 3.75h6.885q.269 0 .442-.174q.173-.172.173-.442V7.5q0-.27-.173-.442q-.173-.173-.442-.173H12.5v2.75h1.212q.666 0 1.14.474q.475.475.475 1.141v1.52q0 .666-.474 1.14t-1.141.475H12.5zM4 13.385v-2.75z");
}

</style>
