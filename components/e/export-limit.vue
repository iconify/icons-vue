<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xssyjpb0u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:export-limit" /></template>
<style>
.xssyjpb0u {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M15.464 11.5H5.682q-.098 0-.195-.011q-.098-.011-.193-.032q-.096-.022-.188-.054q-.093-.033-.181-.075q-.089-.042-.172-.094t-.16-.113q-.076-.061-.146-.13t-.131-.146t-.113-.159t-.096-.171t-.075-.181q-.033-.092-.055-.187q-.022-.096-.034-.193q-.011-.097-.012-.195q0-.098.01-.196q.011-.097.032-.193l1.222-5.5q.032-.145.088-.282t.135-.263t.177-.237t.214-.203q.115-.093.245-.165t.27-.121t.286-.074t.294-.025h10.192q.148 0 .294.025q.147.025.286.074q.14.049.27.121t.245.165t.214.203q.099.111.177.237q.079.126.135.263t.088.282l1.222 5.5q.021.094.031.191q.011.096.011.192q0 .097-.011.193t-.032.191q-.022.094-.053.185q-.032.092-.074.179t-.092.17t-.11.158t-.128.145t-.142.131t-.156.113t-.168.096t-.177.077q-.091.034-.184.057q-.094.024-.19.036q-.096.013-.193.016M12 2.5v9M4.5 7h15m-11 4.5V21m-3 0h6m4-6.75h6m-3 2.75v5m-2.25-2.75L18.5 17l2.25 2.25");
}

</style>
