<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q3y87fblk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:file-lock" /></template>
<style>
.q3y87fblk {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M13.5 1.75H7q-1.346 0-2.298.952T3.75 5v14q0 1.346.952 2.298T7 22.25h10q1.346 0 2.298-.952T20.25 19V8.5q0 .074-.014.146q-.015.073-.043.141t-.069.13t-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014h-4q-2.75 0-2.75-2.75v-4q0-.074.014-.146q.015-.073.043-.141t.069-.13t.094-.113q.052-.053.113-.094t.13-.069t.141-.043q.072-.014.146-.014m.531.22q.105.106.162.243q.057.138.057.287v4q0 1.25 1.25 1.25h4q.149 0 .287.057t.243.163zM11 13.25v-.5q0-1 1-1q.414 0 .707.293t.293.707v.5zm3.5.328q.275.162.518.404q.732.732.732 1.768v1q0 1.036-.732 1.768t-1.768.732h-2.5q-1.036 0-1.768-.732T8.25 16.75v-1q0-1.768 1.25-2.286v-.714q0-2.5 2.5-2.5q1.036 0 1.768.732t.732 1.768z");
}

</style>
