<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p-frsxbno"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:captcha" /></template>
<style>
.p-frsxbno {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M17.125 4.25H6.875q-2.123 0-3.624 1.501T1.75 9.375v5.25q0 2.123 1.501 3.624t3.624 1.501h10.25q2.123 0 3.624-1.501t1.501-3.624v-5.25q0-2.123-1.501-3.624T17.125 4.25m-9.875 4h2.5q2.5 0 2.5 2.5v2.5q0 1.036-.732 1.768t-1.768.732h-2.5q-1.036 0-1.768-.732T4.75 13.25v-2.5q0-2.5 2.5-2.5m11.25 3q.074 0 .146.014q.073.015.141.043t.13.069q.061.041.113.094q.053.052.094.113t.069.13t.043.141t.014.146t-.014.146q-.015.073-.043.141t-.069.13t-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014H14q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069t-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141T13.25 12t.014-.146q.015-.073.043-.141t.069-.13t.094-.113q.052-.053.113-.094t.13-.069t.141-.043t.146-.014z");
}

</style>
