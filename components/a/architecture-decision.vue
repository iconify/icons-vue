<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uymfq09ok"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:architecture-decision" /></template>
<style>
.uymfq09ok {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M13.5 1.75H7q-1.346 0-2.298.952T3.75 5v14q0 1.346.952 2.298T7 22.25h10q1.346 0 2.298-.952T20.25 19V8.5q0 .074-.014.146q-.015.073-.043.141t-.069.13t-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014h-4q-2.75 0-2.75-2.75v-4q0-.074.014-.146q.015-.073.043-.141t.069-.13t.094-.113q.052-.053.113-.094t.13-.069t.141-.043q.072-.014.146-.014m.531.22q.105.106.162.243q.057.138.057.287v4q0 1.25 1.25 1.25h4q.149 0 .287.057t.243.163zM11 8.75q1.75 0 1.75 1.75q0 1.323-1 1.646v1.329l1.532 1.811q.216-.036.468-.036q1.75 0 1.75 1.75t-1.75 1.75T12 17q0-.443.112-.774L11 14.911l-1.112 1.315Q10 16.557 10 17q0 1.75-1.75 1.75T6.5 17t1.75-1.75q.252 0 .468.036l1.532-1.811v-1.329q-1-.323-1-1.646q0-1.75 1.75-1.75");
}

</style>
