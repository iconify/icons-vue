<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d8rxcrg1t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:basketball-net" /></template>
<style>
.d8rxcrg1t {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M3.379 5.26q-.129.346-.129.74q0 .45.168.838l2.85 12.825q.014.062.038.121t.057.112t.076.102q.042.047.092.087t.105.071t.115.052t.123.031t.126.011h10q.064 0 .126-.011q.063-.01.123-.031q.06-.022.115-.052q.056-.031.105-.071q.05-.04.092-.087q.042-.048.076-.102t.057-.112q.024-.059.038-.121l2.85-12.825q.168-.388.168-.838q0-3.25-8.75-3.25q-7.689 0-8.621 2.51m11.363 3.895L12 13.795l-2.742-4.64Q10.5 9.25 12 9.25t2.742-.095m-3.613 6.114L9.072 18.75h-1.47L5.298 8.384q.862.342 2.086.548zm-.315 3.481L12 16.743l1.186 2.007zm2.057-3.481l3.745-6.337q1.224-.206 2.086-.548L16.398 18.75h-1.47z");
}

</style>
