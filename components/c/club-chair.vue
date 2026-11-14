<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lfbew5baf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:club-chair" /></template>
<style>
.lfbew5baf {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M17.125 3.75H6.875q-2.123 0-3.624 1.501T1.75 8.875v3.75q0 2.123 1.501 3.624q.469.469.999.792V20.5q0 .074.014.146q.015.073.043.141t.069.13q.041.061.094.113q.052.053.113.094t.13.069t.141.043t.146.014t.146-.014q.073-.015.141-.043t.13-.069q.061-.041.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146v-2.864q.539.114 1.125.114h10.25q.586 0 1.125-.114V20.5q0 .074.014.146q.015.073.043.141t.069.13q.041.061.094.113q.052.053.113.094t.13.069t.141.043t.146.014q.074 0 .146-.014q.073-.015.141-.043t.13-.069q.061-.041.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146v-3.459q.53-.323.999-.792q1.501-1.501 1.501-3.624v-3.75q0-2.123-1.501-3.624T17.125 3.75");
}

</style>
