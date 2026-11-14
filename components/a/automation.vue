<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ell3vp39i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:automation" /></template>
<style>
.ell3vp39i {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("m20.53 4.47l-2.5-2.5q-.052-.053-.113-.094t-.13-.069t-.141-.043t-.146-.014t-.146.014q-.073.015-.141.043t-.13.069q-.061.041-.113.094q-.106.105-.163.243t-.057.287t.057.287t.163.243l1.219 1.22H10q-1.76 0-3.005 1.245T5.75 8.5t1.245 3.005T10 12.75h4q2.75 0 2.75 2.75T14 18.25H7.44q-.345-2-2.69-2Q2 16.25 2 19t2.75 2.75q2.345 0 2.69-2H14q1.76 0 3.005-1.245T18.25 15.5t-1.245-3.005T14 11.25h-4q-1.139 0-1.945-.805Q7.25 9.639 7.25 8.5q0-2.75 2.75-2.75h8.189L16.97 6.97q-.106.105-.163.243t-.057.287t.057.287t.163.243q.052.053.113.094t.13.069t.141.043t.146.014t.146-.014q.073-.015.141-.043t.13-.069q.061-.041.113-.094l2.5-2.5q.106-.105.163-.243T20.75 5t-.057-.287t-.163-.243");
}

</style>
