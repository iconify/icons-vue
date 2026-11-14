<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qy94eytnm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:gemba-walk" /></template>
<style>
.qy94eytnm {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M7.5 3Q4 3 4 7.75t3.5 4.75T11 7.75T7.5 3m5.5 8q0-4.75 3.5-4.75T20 11t-3.5 4.75T13 11m-5.5 1.75q-3 0-3 2.5t3 2.5t3-2.5t-3-2.5m6 5.751v-.002q0-1.091.948-1.829q.862-.671 2.052-.671t2.052.671q.949.738.948 1.829q.001 1.093-.948 1.831q-.862.671-2.052.671t-2.052-.671q-.948-.738-.948-1.829");
}

</style>
