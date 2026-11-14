<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="luifdzrhr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:claim-status" /></template>
<style>
.luifdzrhr {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M13.5 1.75H7q-1.346 0-2.298.952T3.75 5v14q0 1.346.952 2.298T7 22.25h10q1.346 0 2.298-.952T20.25 19V8.5q0 .074-.014.146q-.015.073-.043.141t-.069.13t-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014h-4q-2.75 0-2.75-2.75v-4q0-.074.014-.146q.015-.073.043-.141t.069-.13t.094-.113q.052-.053.113-.094t.13-.069t.141-.043q.072-.014.146-.014m.531.22q.105.106.162.243q.057.138.057.287v4q0 1.25 1.25 1.25h4q.149 0 .287.057t.243.163zm-5.036 9.525Q10.24 10.25 12 10.25t3.005 1.245T16.25 14.5t-1.245 3.005T12 18.75t-3.005-1.245T7.75 14.5t1.245-3.005");
}

</style>
