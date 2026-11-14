<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n79jd-kvd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:basic-calculator" /></template>
<style>
.n79jd-kvd {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M15.125 1.75h-6.25q-2.123 0-3.624 1.501T3.75 6.875v10.25q0 2.123 1.501 3.624t3.624 1.501h6.25q2.123 0 3.624-1.501t1.501-3.624V6.875q0-2.123-1.501-3.624T15.125 1.75m-5.875 3h5.5q2.5 0 2.5 2.5q0 1.036-.732 1.768t-1.768.732h-5.5q-1.036 0-1.768-.732T6.75 7.25q0-2.5 2.5-2.5M9 11.25h.5q2.25 0 2.25 2.25v.5q0 .932-.659 1.591T9.5 16.25h.5q1.75 0 1.75 1.75T10 19.75H8.5q-1.75 0-1.75-1.75t1.75-1.75H9q-.932 0-1.591-.659T6.75 14v-.5q0-2.25 2.25-2.25m3.25 2.25q0-2.25 2.25-2.25h.5q2.25 0 2.25 2.25v.5q0 .932-.659 1.591T15 16.25h.5q1.75 0 1.75 1.75t-1.75 1.75H14q-1.75 0-1.75-1.75T14 16.25h.5q-.932 0-1.591-.659T12.25 14z");
}

</style>
