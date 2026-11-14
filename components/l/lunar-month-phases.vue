<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zo5eprnki"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:lunar-month-phases" /></template>
<style>
.zo5eprnki {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M5.5 8.25q.138 0 .268.049q.129.05.232.142q.055.049.099.108t.077.126t.05.138t.023.145q.004.074-.006.147t-.035.143t-.062.133q-.038.064-.087.119q-2.236 2.5 0 5q.092.103.142.232q.049.13.049.268q0 .074-.014.146q-.015.073-.043.141t-.069.13t-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014q-3.75 0-3.75-3.75T5.5 8.25m6.5 0q-3.75 0-3.75 3.75T12 15.75T15.75 12T12 8.25m6.5 0q3.75 0 3.75 3.75t-3.75 3.75q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069q-.061-.041-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141T17.75 15q0-.138.049-.268q.05-.129.142-.232q2.236-2.5 0-5q-.049-.055-.087-.119q-.037-.063-.062-.133q-.024-.07-.035-.143q-.01-.073-.006-.147q.004-.073.023-.145q.018-.072.05-.138t.077-.126q.044-.059.099-.108q.103-.092.232-.142q.13-.049.268-.049");
}

</style>
