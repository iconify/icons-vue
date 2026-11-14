<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lhyf00bnj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:heart-suit" /></template>
<style>
.lhyf00bnj {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M8.375 1.75h7.25q2.123 0 3.624 1.501t1.501 3.624v10.25q0 2.123-1.501 3.624t-3.624 1.501h-7.25q-2.123 0-3.624-1.501T3.25 17.125V6.875q0-2.123 1.501-3.624T8.375 1.75m-.201 7.73q.043.053.096.096q.057.047.121.083q.065.035.136.057q.07.022.144.03t.147.001t.144-.028t.137-.055q.065-.034.122-.081q.058-.046.105-.103l1.124-1.348q.746-.328.954-1.166q.238-.96-.461-1.659t-1.659-.461q-.3.074-.534.217q-.234-.143-.534-.217q-.96-.238-1.659.461t-.461 1.659q.208.838.954 1.166z");
}

</style>
