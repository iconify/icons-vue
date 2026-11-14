<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tqmu9oblw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:business-network" /></template>
<style>
.tqmu9oblw {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M11.25 7.446Q9 7.098 9 4.5q0-3 3-3q1.243 0 2.121.879Q15 3.257 15 4.5q0 2.598-2.25 2.946v2.103q2.5.351 2.5 3.201q0 .789-.192 1.386l2.407 1.926q.737-.562 2.035-.562q3 0 3 3t-3 3t-3-3q0-.659.145-1.174l-2.43-1.943Q13.416 16 12 16t-2.215-.617l-2.43 1.943q.145.515.145 1.174q0 3-3 3t-3-3q0-1.243.879-2.121q.878-.879 2.121-.879q1.298 0 2.035.562l2.407-1.926q-.192-.597-.192-1.386q0-2.85 2.5-3.201z");
}

</style>
