<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lviloc2ag"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:graph-query" /></template>
<style>
.lviloc2ag {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M5.5 2.25q-3.25 0-3.25 3.25q0 2.85 2.5 3.201v2.598q-2.5.351-2.5 3.201q0 3.25 3.25 3.25t3.25-3.25q0-2.85-2.5-3.201V8.701Q8.4 8.4 8.701 6.25h2.598q.351 2.5 3.201 2.5q3.25 0 3.25-3.25T14.5 2.25q-2.85 0-3.201 2.5H8.701Q8.35 2.25 5.5 2.25m5.964 9.214Q10 12.929 10 15t1.464 3.536Q12.929 20 15 20q1.686 0 2.969-.97l3.001 3q.052.053.113.094t.13.069t.141.043t.146.014q.074 0 .146-.014q.073-.015.141-.043t.13-.069q.061-.041.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146q0-.074-.014-.146q-.015-.073-.043-.141t-.069-.13q-.041-.061-.094-.113l-3-3.001Q20 16.686 20 15q0-2.071-1.464-3.536Q17.071 10 15 10t-3.536 1.464");
}

</style>
