<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bgrh56bbb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:greenhouse-fan" /></template>
<style>
.bgrh56bbb {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M17.625 1.25H6.375q-2.123 0-3.624 1.501T1.25 6.375v11.25q0 2.123 1.501 3.624t3.624 1.501h11.25q2.123 0 3.624-1.501t1.501-3.624V6.375q0-2.123-1.501-3.624T17.625 1.25M10.85 9.405q-.7-1.63-.325-3.036Q11.09 4.25 13.5 4.25q.149 0 .287.057t.243.163q1.451 1.451.941 3.236q-.302 1.059-1.258 1.954q.637.4.882 1.19q1.63-.7 3.036-.325q2.119.565 2.119 2.975q0 .149-.057.287t-.163.243q-1.451 1.451-3.236.941q-1.059-.302-1.954-1.258q-.4.637-1.19.882q.7 1.63.325 3.036q-.565 2.119-2.975 2.119q-.149 0-.287-.057t-.243-.163q-1.451-1.451-.941-3.236q.302-1.059 1.258-1.954q-.637-.4-.882-1.19q-1.63.7-3.036.325Q4.25 12.91 4.25 10.5q0-.149.057-.287t.163-.243q1.451-1.451 3.236-.941q1.059.302 1.954 1.258q.4-.637 1.19-.882");
}

</style>
