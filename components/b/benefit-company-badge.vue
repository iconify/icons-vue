<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p5mxrvbnm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:benefit-company-badge" /></template>
<style>
.p5mxrvbnm {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M20.577 14.21q1.915-2.21 0-4.42l-1.418-1.637q-.245-.282-.363-.635l-.594-1.784q-.952-2.856-3.898-2.236l-1.918.404q-.386.081-.772 0l-1.919-.404q-2.945-.62-3.896 2.236l-.595 1.784q-.118.353-.363.635L3.423 9.79q-1.915 2.21 0 4.42l1.418 1.637q.245.282.363.635l.594 1.784q.952 2.856 3.898 2.236l1.918-.404q.386-.081.772 0l1.919.404q2.945.62 3.896-2.236l.595-1.784q.118-.353.363-.635zm-9.827-.521l4.47-4.469q.052-.053.113-.094t.13-.069t.141-.043T15.75 9t.146.014q.073.015.141.043t.13.069q.061.041.113.094q.106.105.163.243t.057.287t-.057.287t-.163.243l-5 5q-.105.106-.243.163t-.287.057t-.287-.057t-.243-.163l-2.5-2.5q-.106-.105-.163-.243T7.5 12.25t.057-.287t.163-.243q.052-.053.113-.094t.13-.069t.141-.043t.146-.014t.146.014q.073.015.141.043t.13.069t.113.094z");
}

</style>
