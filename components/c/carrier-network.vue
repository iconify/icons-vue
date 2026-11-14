<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v0hv54bwc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:carrier-network" /></template>
<style>
.v0hv54bwc {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M15 5.5q0-3-3-3t-3 3q0 2.598 2.25 2.946v2.353q-2.5.351-2.5 3.201q0 .498.076.92l-1.835 1.071q-.75-.741-2.241-.741q-3 0-3 3t3 3t3-3q0-.5-.083-.916l1.77-1.033q.807.949 2.563.949t2.563-.949l1.813 1.058q-.126.419-.126.89v.002q0 1.242.878 2.121q.879.88 2.122.88t2.122-.88t.878-2.123q.001-1.242-.878-2.121q-.879-.88-2.122-.88q-1.213 0-2.079.838l-1.997-1.166q.076-.422.076-.92q0-2.85-2.5-3.201V8.446Q15 8.098 15 5.5");
}

</style>
