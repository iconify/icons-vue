<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xzxr8lbef"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:analytics-rounded" /></template>
<style>
.xzxr8lbef {
  fill: currentColor;
  d: path("M7.874 12.144q-.143.144-.143.356V16q0 .213.144.356t.356.144t.357-.144T8.73 16v-3.5q0-.213-.144-.356Q8.443 12 8.23 12t-.356.144m7.539-5q-.144.144-.144.356V16q0 .213.144.356q.144.144.357.144t.356-.144t.143-.356V7.5q0-.213-.144-.356T15.77 7t-.356.144m-3.77 7q-.143.144-.143.356V16q0 .213.144.356t.357.144t.356-.144T12.5 16v-1.5q0-.213-.144-.356T11.999 14t-.356.144M5.616 20q-.691 0-1.153-.462T4 18.384V5.616q0-.691.463-1.153T5.616 4h12.769q.69 0 1.153.463T20 5.616v12.769q0 .69-.462 1.153T18.384 20zm6.74-8.644q.144-.144.144-.357t-.144-.356t-.357-.143t-.356.144t-.143.357t.144.356t.357.143t.356-.144");
}

</style>
