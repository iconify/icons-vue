<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="miq-rrnqx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:add-column-right-outline-rounded" /></template>
<style>
.miq-rrnqx {
  fill: currentColor;
  d: path("M10.558 5H4.616q-.27 0-.443.173T4 5.616v12.769q0 .269.173.442t.443.173h5.942zM4.616 20q-.667 0-1.141-.475T3 18.386V5.615q0-.666.475-1.14T4.615 4h12.77q.666 0 1.14.475T19 5.615v1q0 .213-.144.357t-.357.144t-.356-.144T18 6.616v-1q0-.27-.173-.443T17.385 5h-5.827v14h5.827q.269 0 .442-.173t.173-.442v-1q0-.213.144-.357t.357-.143t.356.143t.143.357v1q0 .666-.475 1.14t-1.14.475zm13.527-5.644Q18 14.213 18 14v-1.5h-1.5q-.213 0-.356-.144T16 11.999t.144-.356t.356-.143H18V10q0-.213.144-.356t.357-.144t.356.144T19 10v1.5h1.5q.213 0 .356.144t.144.357t-.144.356t-.356.143H19V14q0 .213-.144.356t-.357.144t-.356-.144M10.558 12h1zm0 0");
}

</style>
