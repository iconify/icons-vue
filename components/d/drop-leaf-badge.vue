<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y_a7wvbtu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:drop-leaf-badge" /></template>
<style>
.y_a7wvbtu {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M11.45 1.99q.019-.021.04-.04q.109-.101.249-.153t.289-.046q.149.005.284.067q.136.062.238.172q6.7 7.215 6.7 12.51q0 3.003-2.123 5.127T12 21.75t-5.127-2.123Q4.75 17.503 4.75 14.5q0-5.295 6.7-12.51m3.05 8.76q-5.75 0-5.75 6.25q0 .149.057.287t.163.243q.027.028.057.052q.101.082.222.125q.122.043.251.043q5.75 0 5.75-6.25q0-.074-.014-.146q-.015-.073-.043-.141t-.069-.13t-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043t-.146-.014");
}

</style>
