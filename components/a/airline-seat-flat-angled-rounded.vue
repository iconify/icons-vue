<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ti5d3mb-f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:airline-seat-flat-angled-rounded" /></template>
<style>
.ti5d3mb-f {
  fill: currentColor;
  d: path("m9.4 11.775l1.375-3.75Q11.05 7.25 11.8 6.9t1.525-.075l6.575 2.4q1.575.575 2.275 2.063t.125 3.062l-.675 1.875q-.15.4-.525.575t-.775.025L10 13.075q-.4-.15-.575-.525t-.025-.775m9.875 7.875L2.35 13.5q-.4-.125-.562-.5t-.038-.775t.513-.575t.787-.025l16.925 6.15q.4.125.563.5t.037.775t-.512.575t-.788.025M4.2 10.675Q3.325 9.8 3.325 8.55T4.2 6.425t2.125-.875t2.125.875t.875 2.125t-.875 2.125t-2.125.875t-2.125-.875");
}

</style>
