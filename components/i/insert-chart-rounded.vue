<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h1itd6-dk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:insert-chart-rounded" /></template>
<style>
.h1itd6-dk {
  fill: currentColor;
  d: path("M5.616 20q-.691 0-1.153-.462T4 18.384V5.616q0-.691.463-1.153T5.616 4h12.769q.69 0 1.153.463T20 5.616v12.769q0 .69-.462 1.153T18.384 20zm2.258-9.356q-.143.143-.143.356v5q0 .212.144.356t.357.144t.356-.144T8.73 16v-5q0-.213-.144-.356q-.144-.144-.357-.144t-.356.144m3.77-3Q11.5 7.788 11.5 8v8q0 .213.144.356t.357.144t.356-.144T12.5 16V8q0-.213-.144-.356t-.357-.144t-.356.144m3.77 6q-.144.144-.144.356v2q0 .213.144.356q.144.144.357.144t.356-.144t.143-.356v-2q0-.213-.144-.356t-.356-.144t-.356.144");
}

</style>
