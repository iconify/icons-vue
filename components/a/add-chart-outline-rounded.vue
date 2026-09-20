<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="evomvom4f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:add-chart-outline-rounded" /></template>
<style>
.evomvom4f {
  fill: currentColor;
  d: path("M5.116 20q-.691 0-1.153-.462T3.5 18.384V5.616q0-.691.463-1.153T5.115 4h8.808q.213 0 .356.144t.144.357t-.144.356t-.356.143H5.116q-.27 0-.443.173t-.173.443v12.769q0 .269.173.442t.443.173h12.769q.269 0 .442-.173t.173-.443V9.577q0-.213.144-.356t.357-.144t.356.144t.143.356v8.808q0 .69-.462 1.152T17.884 20zm2.258-9.356q-.143.143-.143.356v5q0 .212.144.356t.357.144t.356-.144T8.23 16v-5q0-.213-.144-.356q-.144-.144-.357-.144t-.356.144m3.77-3Q11 7.788 11 8v8q0 .213.144.356t.357.144t.356-.144T12 16V8q0-.213-.144-.356t-.357-.144t-.356.144m3.77 6q-.144.144-.144.356v2q0 .213.144.356q.144.144.357.144t.356-.144t.143-.356v-2q0-.213-.144-.356t-.356-.144t-.356.144M17.5 6H16q-.213 0-.356-.144t-.144-.357t.144-.356T16 5h1.5V3.5q0-.213.144-.356T18.001 3t.356.144t.143.356V5H20q.213 0 .356.144t.144.357t-.144.356T20 6h-1.5v1.5q0 .213-.144.356T17.999 8t-.356-.144T17.5 7.5zm-6 6");
}

</style>
