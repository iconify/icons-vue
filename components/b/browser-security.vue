<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jvmb2175w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:browser-security" /></template>
<style>
.jvmb2175w {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M17.125 2.25H6.875q-2.123 0-3.624 1.501T1.75 7.375v9.25q0 2.123 1.501 3.624t3.624 1.501h10.25q2.123 0 3.624-1.501t1.501-3.624v-9.25q0-2.123-1.501-3.624T17.125 2.25M22.25 7.5q0 .074-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014h-19q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069t-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141T1.75 7.5t.014-.146q.015-.073.043-.141t.069-.13q.041-.061.094-.113q.052-.053.113-.094t.13-.069t.141-.043t.146-.014h19q.074 0 .146.014q.073.015.141.043t.13.069q.061.041.113.094q.053.052.094.113t.069.13t.043.141t.014.146M9.5 12.627v-.377q0-2.5 2.5-2.5q1.036 0 1.768.732t.732 1.768v.377Q16 13.064 16 15v1.5q0 2.5-2.5 2.5h-3Q8 19 8 16.5V15q0-1.936 1.5-2.373M11 12.5v-.25q0-1 1-1q.414 0 .707.293t.293.707v.25z");
}

</style>
