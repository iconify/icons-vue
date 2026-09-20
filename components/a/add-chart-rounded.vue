<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v1zg49b1l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:add-chart-rounded" /></template>
<style>
.v1zg49b1l {
  fill: currentColor;
  d: path("M8.088 16.356q.143-.144.143-.356v-5q0-.213-.144-.356q-.144-.144-.357-.144t-.356.144t-.143.356v5q0 .213.144.356t.357.144t.356-.144m3.769 0Q12 16.213 12 16V8q0-.213-.144-.356t-.357-.144t-.356.144T11 8v8q0 .213.144.356t.357.144t.356-.144m3.769 0q.143-.144.143-.356v-2q0-.213-.144-.356t-.356-.144t-.356.144t-.144.356v2q0 .213.144.356q.144.144.357.144t.356-.144m2.017-8.5Q17.5 7.713 17.5 7.5V6H16q-.213 0-.356-.144t-.144-.357t.144-.356T16 5h1.5V3.5q0-.213.144-.356T18.001 3t.356.144t.143.356V5H20q.213 0 .356.144t.144.357t-.144.356T20 6h-1.5v1.5q0 .213-.144.356T17.999 8t-.356-.144M5.116 20q-.691 0-1.153-.462T3.5 18.384V5.616q0-.691.463-1.153T5.115 4h8.808q.213 0 .356.144t.144.356v2.962q0 .666.475 1.14t1.14.475H19q.213 0 .356.144t.144.356v8.808q0 .69-.462 1.153T17.884 20z");
}

</style>
