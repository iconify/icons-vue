<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xwqyt4b_z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:coping-toolbox" /></template>
<style>
.xwqyt4b_z {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("m15.621 2.891l-1.88-.685h-.001q-2.114-.768-2.883 1.345q-.137.376-.142.747L6.372 2.717h-.001q-1.879-.684-2.563 1.196t1.195 2.563l11.744 4.274H12.25q2.25 0 2.25 2.25t-2.25 2.25h-.5Q9.5 15.25 9.5 13t2.25-2.25H5.625q-1.398 0-2.386.989q-.989.988-.989 2.386v4.25q0 1.398.989 2.386q.988.989 2.386.989h12.75q3.375 0 3.375-3.375v-4.25q0-1.55-.712-2.388l.06-.027q.751-.35 1.035-1.129q.283-.778-.068-1.529q-.35-.751-1.128-1.034l-4.3-1.565q.187-.291.328-.679q.768-2.113-1.344-2.883");
}

</style>
