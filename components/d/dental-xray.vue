<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z-ys_lbdz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:dental-xray" /></template>
<style>
.z-ys_lbdz {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M15.125 1.75h-6.25q-2.123 0-3.624 1.501T3.75 6.875v10.25q0 2.123 1.501 3.624t3.624 1.501h6.25q2.123 0 3.624-1.501t1.501-3.624V6.875q0-2.123-1.501-3.624T15.125 1.75m-5.625 3q.852 0 1.762.499q.458.251.738.251t.738-.251q.91-.499 1.762-.499q3 0 3 3.75q0 1.169-.728 2.827q-.435.991-.529 1.53l-.498 4.231l-.005.035q-.292 1.752-1.74 1.752t-1.74-1.752l-.007-.055l-.239-2.625q-.006-.005-.014-.005t-.014.005l-.239 2.625l-.007.055q-.292 1.752-1.74 1.752t-1.74-1.752l-.005-.035l-.498-4.231q-.094-.539-.529-1.53Q6.5 9.669 6.5 8.5q0-3.75 3-3.75");
}

</style>
