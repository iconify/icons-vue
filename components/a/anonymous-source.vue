<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gr91p-97z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:anonymous-source" /></template>
<style>
.gr91p-97z {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M2.75 20v1.5q0 .074.014.146q.015.073.043.141t.069.13q.041.061.094.113q.052.053.113.094t.13.069t.141.043t.146.014h17q.074 0 .146-.014q.073-.015.141-.043t.13-.069q.061-.041.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146V20q0-3.439-2.5-4.943V10q0-6.041-6.513-8.212q-.115-.038-.237-.038t-.237.038Q5.25 3.959 5.25 10v5.057Q2.75 16.561 2.75 20m5.5-9q0-1.816 1.043-3.12Q10.397 6.5 12 6.5t2.707 1.38Q15.75 9.184 15.75 11t-1.043 3.12Q13.603 15.5 12 15.5t-2.707-1.38Q8.25 12.816 8.25 11");
}

</style>
