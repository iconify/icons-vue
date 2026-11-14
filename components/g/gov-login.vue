<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y0dqnxcfj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:gov-login" /></template>
<style>
.y0dqnxcfj {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M6 2.25h12q1.76 0 3.005 1.245T22.25 6.5V13q0 1.76-1.245 3.005T18 17.25h-5.25v2.5h2.75q.074 0 .146.014q.073.015.141.043t.13.069t.113.094q.053.052.094.113t.069.13t.043.141t.014.146q0 .074-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014h-7q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069t-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141t-.014-.146q0-.074.014-.146q.015-.073.043-.141t.069-.13q.041-.061.094-.113q.052-.053.113-.094t.13-.069t.141-.043t.146-.014h2.75v-2.5H6q-1.76 0-3.005-1.245T1.75 13V6.5q0-1.76 1.245-3.005T6 2.25m4.75 6.5h2.5V8q0-1.25-1.25-1.25T10.75 8zm4 .2V8q0-2.75-2.75-2.75T9.25 8v.877q-1.5.437-1.5 2.373v.5q0 2.5 2.5 2.5h3.5q1.036 0 1.768-.732t.732-1.768v-.5q0-1.036-.732-1.768q-.35-.349-.768-.532");
}

</style>
