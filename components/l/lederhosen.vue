<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h8f2prb-e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:lederhosen" /></template>
<style>
.h8f2prb-e {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M7.75 7V3.5q0-.074.014-.146q.015-.073.043-.141t.069-.13t.094-.113q.052-.053.113-.094t.13-.069t.141-.043q.072-.014.146-.014t.146.014q.073.015.141.043t.13.069t.113.094q.053.052.094.113t.069.13t.043.141t.014.146v2.75h5.5V3.5q0-.074.014-.146q.015-.073.043-.141t.069-.13t.094-.113q.052-.053.113-.094t.13-.069t.141-.043q.072-.014.146-.014t.146.014q.073.015.141.043t.13.069t.113.094q.053.052.094.113t.069.13t.043.141t.014.146v7.25h.226q2.177-.001 2.477 2.156l.764 5.5q.157 1.127-.591 1.986q-.748.858-1.886.858h-2.438q-1.86 0-2.394-1.781l-.376-1.253q-.007-.024-.032-.024t-.032.023l-.376 1.254q-.534 1.781-2.394 1.781H6.76q-1.138 0-1.886-.858q-.748-.859-.591-1.986l.764-5.5q.3-2.157 2.477-2.156h.226zm1.5.75v3h5.5v-3z");
}

</style>
