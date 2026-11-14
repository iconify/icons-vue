<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m_gw_i7zc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:breathing-apparatus" /></template>
<style>
.m_gw_i7zc {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M11 2.25q8.75 0 8.75 7.75q0 1.218-.212 2.373Q18.597 12 17.5 12q-2.278 0-3.889 1.611T12 17.5q0 1.939 1.167 3.395q-1.035.355-2.167.355q-3.646 0-6.297-3.687Q2.25 14.149 2.25 10q0-7.75 8.75-7.75m-3.5 4.5q-2.75 0-2.75 2.75t2.75 2.75t2.75-2.75T7.5 6.75m4.25 2.75q0 2.75 2.75 2.75t2.75-2.75t-2.75-2.75t-2.75 2.75m1.5 8q0-1.76 1.245-3.005T17.5 13.25t3.005 1.245T21.75 17.5t-1.245 3.005T17.5 21.75t-3.005-1.245T13.25 17.5m1.5 0q0 2.75 2.75 2.75t2.75-2.75t-2.75-2.75t-2.75 2.75M17.5 16q.411 0 .71.113q-.404.741-.913 1.45q-.43.597-.885 1.097Q16 18.286 16 17.5q0-1.5 1.5-1.5");
}

</style>
