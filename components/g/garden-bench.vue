<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rzbmpp24r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:garden-bench" /></template>
<style>
.rzbmpp24r {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M18.25 1.75H5.75q-1.036 0-1.768.732T3.25 4.25v1.5q0 1.036.732 1.768t1.768.732v2H4q-2.25 0-2.25 2.25q0 .932.659 1.591T4 14.75h.25V21q0 .074.014.146q.015.073.043.141t.069.13q.041.061.094.113q.052.053.113.094t.13.069t.141.043t.146.014t.146-.014q.073-.015.141-.043t.13-.069q.061-.041.113-.094q.053-.052.094-.113t.069-.13t.043-.141T5.75 21v-6.25h12.5V21q0 .074.014.146q.015.073.043.141t.069.13q.041.061.094.113q.052.053.113.094t.13.069t.141.043t.146.014q.074 0 .146-.014q.073-.015.141-.043t.13-.069q.061-.041.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146v-6.25H20q.932 0 1.591-.659t.659-1.591q0-2.25-2.25-2.25h-1.75v-2q1.036 0 1.768-.732t.732-1.768v-1.5q0-2.5-2.5-2.5m-1.5 6.5v2h-9.5v-2z");
}

</style>
