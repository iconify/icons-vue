<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yt6g9kb2j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:active-users" /></template>
<style>
.yt6g9kb2j {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M6.25 7.5q0-1.968 1.391-3.359T11 2.75t3.359 1.391T15.75 7.5t-1.391 3.359T11 12.25t-3.359-1.391T6.25 7.5m8.214 6.964Q13 15.929 13 18t1.464 3.536q.112.111.227.214H4.5q-1.75 0-1.75-1.75q0-2.798 2.468-4.577Q7.538 13.75 11 13.75q2.004 0 3.625.56q-.081.075-.161.154M14.25 18q0-3.75 3.75-3.75T21.75 18T18 21.75T14.25 18m1.5 0q0 2.25 2.25 2.25T20.25 18T18 15.75T15.75 18m3.23.261q-.212-.641-.593-1.214Q18.217 17 18 17q-1 0-1 1t1 1q.86 0 .98-.739");
}

</style>
