<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dl3hwj75a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:induction-hob" /></template>
<style>
.dl3hwj75a {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M18 2.25H6q-1.76 0-3.005 1.245T1.75 6.5v11q0 1.76 1.245 3.005T6 21.75h12q1.76 0 3.005-1.245T22.25 17.5v-11q0-1.76-1.245-3.005T18 2.25M4.75 8.5q0-3.25 3.25-3.25q1.346 0 2.298.952T11.25 8.5t-.952 2.298T8 11.75q-3.25 0-3.25-3.25m13.243 3.568q.757 1.059.757 2.432q0 1.76-1.245 3.005T14.5 18.75t-3.005-1.245T10.25 14.5t1.245-3.005T14.5 10.25q1.373 0 2.432.757L18.47 9.47q.052-.053.113-.094t.13-.069t.141-.043T19 9.25t.146.014q.073.015.141.043t.13.069q.061.041.113.094q.106.105.163.243t.057.287t-.057.287t-.163.243z");
}

</style>
