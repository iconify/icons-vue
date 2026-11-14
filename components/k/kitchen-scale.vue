<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qw_31swrn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:kitchen-scale" /></template>
<style>
.qw_31swrn {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M16 4.25H8q-.074 0-.146.014q-.073.015-.141.043t-.13.069q-.061.041-.113.094q-.053.052-.094.113t-.069.13t-.043.141T7.25 5t.014.146q.015.073.043.141t.069.13q.041.061.094.113q.052.053.113.094t.13.069t.141.043T8 5.75h8q.074 0 .146-.014q.073-.015.141-.043t.13-.069q.061-.041.113-.094q.053-.052.094-.113t.069-.13t.043-.141T16.75 5t-.014-.146q-.015-.073-.043-.141t-.069-.13q-.041-.061-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043T16 4.25m.125 3h-8.25q-2.123 0-3.624 1.501T2.75 12.375v3.25q0 2.123 1.501 3.624t3.624 1.501h8.25q2.123 0 3.624-1.501t1.501-3.624v-3.25q0-2.123-1.501-3.624T16.125 7.25M7.75 14q0-1.76 1.245-3.005T12 9.75t3.005 1.245T16.25 14t-1.245 3.005T12 18.25t-3.005-1.245T7.75 14");
}

</style>
