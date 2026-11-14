<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ocq3-bbdf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:agent-portfolio" /></template>
<style>
.ocq3-bbdf {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M1.75 6.5q0-1.139.805-1.945q.806-.805 1.945-.805H9q.149 0 .287.057t.243.163l1.781 1.78H19.5q2.75 0 2.75 2.75v10q0 2.75-2.75 2.75h-3q.074 0 .146-.014q.073-.015.141-.043t.13-.069q.061-.041.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146q0-5.25-5.25-5.25T6.75 20.5q0 .074.014.146q.015.073.043.141t.069.13q.041.061.094.113q.052.053.113.094t.13.069t.141.043t.146.014h-3q-2.75 0-2.75-2.75zM7.5 21.25q.074 0 .146-.014q.073-.015.141-.043t.13-.069q.061-.041.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146q0-3.75 3.75-3.75t3.75 3.75q0 .074.014.146q.015.073.043.141t.069.13q.041.061.094.113q.052.053.113.094t.13.069t.141.043t.146.014zM12 8.5q-2.75 0-2.75 2.75T12 14t2.75-2.75T12 8.5");
}

</style>
