<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q3-_qcc4c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:cloud-database" /></template>
<style>
.q3-_qcc4c {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M8.75 9.25h6.5l.047-.001q2.748-.172 2.577-2.921q-.072-1.138-.927-1.893q-.648-.571-1.457-.669q-1.029-2.012-3.4-2.201q-2.415-.193-3.756 1.701q-2.584.2-2.584 2.984q0 3 3 3m-4 4q0-2.75 7.25-2.75t7.25 2.75v6.25q0 2.75-7.25 2.75T4.75 19.5zm1.5 5.183V19.5q0 1.25 5.75 1.25t5.75-1.25v-1.067q-1.798.817-5.75.817t-5.75-.817m11.5-1.933q0 1.25-5.75 1.25T6.25 16.5v-1.317Q8.048 16 12 16t5.75-.817z");
}

</style>
