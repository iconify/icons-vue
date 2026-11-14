<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kdz4qzbqe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:macro-shot" /></template>
<style>
.kdz4qzbqe {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M17.125 1.75H6.875q-2.123 0-3.624 1.501T1.75 6.875v10.25q0 2.123 1.501 3.624t3.624 1.501h10.25q2.123 0 3.624-1.501t1.501-3.624V6.875q0-2.123-1.501-3.624T17.125 1.75m.38 6.204q2.769 1.575 1.25 4.375q-.62 1.142-1.457 1.575q.533.932.371 2.045q-.196 1.356-1.304 2.162t-2.459.575q-1.167-.199-1.906-1.068q-.739.869-1.906 1.068q-1.351.231-2.459-.575t-1.304-2.162q-.162-1.113.371-2.045q-.837-.433-1.457-1.575q-1.519-2.8 1.25-4.375q1.25-.711 2.267-.543q.096-1.145.932-1.987q.953-.959 2.306-.959t2.306.959q.836.842.932 1.987q1.017-.168 2.267.543");
}

</style>
