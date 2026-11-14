<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nxvmlebda"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:ballot-paper-fold" /></template>
<style>
.nxvmlebda {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M13.5 1.75H7q-1.346 0-2.298.952T3.75 5v14q0 1.346.952 2.298T7 22.25h10q1.346 0 2.298-.952T20.25 19V8.5q0 .074-.014.146q-.015.073-.043.141t-.069.13t-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014h-4q-2.75 0-2.75-2.75v-4q0-.074.014-.146q.015-.073.043-.141t.069-.13t.094-.113q.052-.053.113-.094t.13-.069t.141-.043q.072-.014.146-.014m.531.22q.105.106.162.243q.057.138.057.287v4q0 1.25 1.25 1.25h4q.149 0 .287.057t.243.163zm-.781 12.729v1.551q0 1.036-.732 1.768t-1.768.732h-1.5q-1.036 0-1.768-.732T6.75 16.25v-1.5q0-2.5 2.5-2.5h1.5q1.036 0 1.768.732q.077.078.147.159l2.543-2.659q.051-.054.112-.096q.06-.043.128-.072q.067-.03.139-.046t.146-.018q.074-.001.147.011t.142.04q.068.027.131.066q.062.04.115.091t.096.112t.072.128q.03.067.046.139t.018.146q.001.074-.011.147t-.04.142t-.066.131q-.04.062-.091.115z");
}

</style>
