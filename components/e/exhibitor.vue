<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zieeu9bzq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:exhibitor" /></template>
<style>
.zieeu9bzq {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M18.25 1.75h-14q-1.036 0-1.768.732T1.75 4.25v.5q0 2.236 2 2.472v2.556q-2 .236-2 2.472v5.5q0 2.5 2.5 2.5h8.327q.332-2.032 2.106-2.884q-.433-.841-.433-2.116q0-3.75 3.75-3.75q1.553 0 2.652 1.098l.098.102v-.45q0-2.236-2-2.472V7.222q2-.236 2-2.472v-.5q0-2.5-2.5-2.5m-13 8v-2.5h12v2.5zm10.25 5.5q0-2.5 2.5-2.5q1.036 0 1.768.732t.732 1.768t-.732 1.768T18 17.75q-2.5 0-2.5-2.5m1.5 0q0 1 1 1q.414 0 .707-.293T19 15.25t-.293-.707T18 14.25q-1 0-1 1m1-.25q.25 0 .25.25t-.25.25t-.25-.25T18 15m0 3q-4.25 0-4.25 3.25q0 1.25 1.25 1.25h6q1.25 0 1.25-1.25Q22.25 18 18 18m2.735 3h-5.47q.189-1.5 2.735-1.5t2.735 1.5");
}

</style>
