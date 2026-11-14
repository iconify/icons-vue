<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pjlok-6_b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:annotation-pin" /></template>
<style>
.pjlok-6_b {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M9.5 4.25q0-2.5 2.5-2.5q1.036 0 1.768.732T14.5 4.25q0 .541-.2 1h4.2q2.75 0 2.75 2.75v7.5q0-.074-.014-.146q-.015-.073-.043-.141t-.069-.13t-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043t-.146-.014H17q-2.75 0-2.75 2.75V21q0 .074.014.146q.015.073.043.141t.069.13q.041.061.094.113q.052.053.113.094t.13.069t.141.043t.146.014H5.5q-2.75 0-2.75-2.75V8q0-1.139.805-1.945q.806-.805 1.945-.805h4.127q-.127-.436-.127-1m6.03 17.28l5.5-5.5q-.105.106-.243.163t-.287.057H17q-1.25 0-1.25 1.25V21q0 .149-.057.287t-.163.243");
}

</style>
