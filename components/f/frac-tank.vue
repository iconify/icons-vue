<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j5_dv2hrw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:frac-tank" /></template>
<style>
.j5_dv2hrw {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M16.75 5.25h-4v-1.5h.75q.074 0 .146-.014q.073-.015.141-.043t.13-.069t.113-.094q.053-.052.094-.113t.069-.13t.043-.141T14.25 3t-.014-.146q-.015-.073-.043-.141t-.069-.13t-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043q-.072-.014-.146-.014h-3q-.074 0-.146.014q-.073.015-.141.043t-.13.069t-.113.094q-.053.052-.094.113t-.069.13t-.043.141T9.75 3t.014.146q.015.073.043.141t.069.13t.094.113q.052.053.113.094t.13.069t.141.043q.072.014.146.014h.75v1.5h-4q-2.278 0-3.889 1.611T1.75 10.75t1.611 3.889q.639.639 1.383 1.024q-.494.672-.494 1.837q0 2.75 2.75 2.75t2.75-2.75q0-.719-.188-1.25h4.876q-.188.531-.188 1.25q0 2.75 2.75 2.75t2.75-2.75q0-1.165-.494-1.837q.744-.385 1.383-1.024q1.611-1.611 1.611-3.889t-1.611-3.889T16.75 5.25");
}

</style>
