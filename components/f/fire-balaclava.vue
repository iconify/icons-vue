<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xnl-i25th"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:fire-balaclava" /></template>
<style>
.xnl-i25th {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M18.75 9.5q0-7.75-6.75-7.75T5.25 9.5V13q0 2.073 1.182 3.287l-2.695 1.011q-.037.014-.072.031q-1.915.957-1.915 4.171q0 .074.014.146q.015.073.043.141t.069.13q.041.061.094.113q.052.053.113.094t.13.069t.141.043t.146.014h19q.074 0 .146-.014q.073-.015.141-.043t.13-.069q.061-.041.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146q0-3.214-1.915-4.171q-.035-.017-.072-.031l-2.695-1.011Q18.75 15.073 18.75 13zM8 10q0-3.25 4-3.25q1.601 0 2.755.888Q16 8.595 16 10q0 3.25-4 3.25T8 10");
}

</style>
