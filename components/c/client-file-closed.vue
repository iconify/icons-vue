<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kys8iu-kw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:client-file-closed" /></template>
<style>
.kys8iu-kw {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M1.75 5.5q0-1.139.805-1.945q.806-.805 1.945-.805H9q.149 0 .287.057t.243.163l1.781 1.78H17.5q2.75 0 2.75 2.75v6.067Q19.408 13 18 13q-3.238 0-3.48 2.995q-1.177.672-1.443 2.255H4.5q-2.75 0-2.75-2.75zm19.268 11.982q-.35-.349-.768-.532v-.45q0-2.25-2.25-2.25t-2.25 2.25v.377q-1.5.437-1.5 2.373v.5q0 1.036.732 1.768t1.768.732h2.5q1.036 0 1.768-.732t.732-1.768v-.5q0-1.036-.732-1.768M18.75 16.5v.25h-1.5v-.25q0-.75.75-.75t.75.75m-3 2.75q0-1 1-1h2.5q.414 0 .707.293t.293.707v.5q0 .414-.293.707t-.707.293h-2.5q-.414 0-.707-.293t-.293-.707z");
}

</style>
