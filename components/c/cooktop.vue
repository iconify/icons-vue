<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gfl5qob5r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:cooktop" /></template>
<style>
.gfl5qob5r {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M7.375 4.25h9.25q2.123 0 3.624 1.501t1.501 3.624v5.25q0 2.123-1.501 3.624t-3.624 1.501h-9.25q-2.123 0-3.624-1.501T2.25 14.625v-5.25q0-2.123 1.501-3.624T7.375 4.25M5.5 9.5q0 1.243.878 2.122q.409.409.897.628q-.488.219-.897.628Q5.5 13.757 5.5 15t.878 2.122t2.122.879t2.122-.879T11.5 15t-.878-2.122q-.409-.409-.897-.628q.488-.219.897-.628q.879-.879.878-2.122q.001-1.243-.878-2.122T8.5 6.499t-2.122.879T5.5 9.5m10-3q-3 0-3 3q0 2.134 1.518 2.75Q12.5 12.866 12.5 15q0 3 3 3t3-3q0-2.134-1.518-2.75Q18.5 11.634 18.5 9.5q0-3-3-3");
}

</style>
