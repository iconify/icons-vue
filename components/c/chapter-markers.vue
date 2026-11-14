<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x7ttt4d8c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:chapter-markers" /></template>
<style>
.x7ttt4d8c {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M13.5 1.75h-7q-1.76 0-3.005 1.245T2.25 6v12q0 1.76 1.245 3.005T6.5 22.25h7q1.76 0 3.005-1.245q1.156-1.155 1.239-2.755H20q1.75 0 1.75-1.75V14q0-1.75-1.75-1.75h-2.25v-2H20q1.75 0 1.75-1.75V6q0-1.75-1.75-1.75h-2.613q-.309-.682-.882-1.255Q15.26 1.75 13.5 1.75m6.5 7h-2.25V6q0-.126-.006-.25H20q.25 0 .25.25v2.5q0 .25-.25.25m-6.5-2.5q.074 0 .146.014q.073.015.141.043t.13.069t.113.094q.053.052.094.113t.069.13t.043.141t.014.146t-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014h-7q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069q-.061-.041-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141T5.75 7t.014-.146q.015-.073.043-.141t.069-.13q.041-.061.094-.113q.052-.053.113-.094t.13-.069t.141-.043t.146-.014zm4.25 7.5H20q.25 0 .25.25v2.5q0 .25-.25.25h-2.25z");
}

</style>
