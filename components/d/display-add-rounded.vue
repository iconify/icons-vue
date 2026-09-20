<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kjs56czqq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:display-add-rounded" /></template>
<style>
.kjs56czqq {
  fill: currentColor;
  d: path("M18 6h-2.5q-.213 0-.356-.144T15 5.499t.144-.356T15.5 5H18V2.5q0-.213.144-.356T18.501 2t.356.144T19 2.5V5h2.5q.213 0 .356.144t.144.357t-.144.356T21.5 6H19v2.5q0 .213-.144.356T18.499 9t-.356-.144T18 8.5zM9 18H4.616q-.691 0-1.153-.462T3 16.384V5.616q0-.691.463-1.153T4.615 4H11.9q.364 0 .586.264q.222.263.16.636q-.03.15-.03.311v.308q0 2.444 1.71 4.155q1.71 1.71 4.155 1.71q.414 0 .806-.059t.763-.158q.373-.106.662.103q.288.209.288.561v4.56q0 .684-.462 1.147T19.385 18H15v1.192q0 .344-.232.576t-.576.232H9.808q-.343 0-.576-.232T9 19.192z");
}

</style>
