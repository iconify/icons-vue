<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jt_ql0r_w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:bimodal-distribution" /></template>
<style>
.jt_ql0r_w {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M2.5 19.75q.016 0 1.051-4.81Q5.637 5.25 8 5.25q2.521 0 3.844 6.874q.124.645.219 1.092l.105-.384Q13.522 7.75 16 7.75q2.337 0 4.442 8.09q1.017 3.91 1.058 3.91q.074 0 .146.014q.073.015.141.043t.13.069q.061.041.113.094q.053.052.094.113t.069.13t.043.141t.014.146q0 .074-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014q-1.201 0-2.51-5.032Q17.177 9.25 16 9.25q-1.326 0-2.383 3.968Q12.942 15.75 12 15.75q-.985 0-1.629-3.343Q9.282 6.75 8 6.75q-1.152 0-2.983 8.505Q3.727 21.25 2.5 21.25q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069t-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141t-.014-.146t.014-.146q.015-.073.043-.141t.069-.13q.041-.061.094-.113q.052-.053.113-.094t.13-.069t.141-.043t.146-.014");
}

</style>
