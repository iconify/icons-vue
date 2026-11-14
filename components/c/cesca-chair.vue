<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="luzhpy09b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:cesca-chair" /></template>
<style>
.luzhpy09b {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M16.25 2.75h1.5q1.036 0 1.768.732t.732 1.768v5q0 1.036-.732 1.768t-1.768.732h-1.5q-.084 0-.165-.005q-.043.005-.085.005H6.5q-1.25 0-1.25 1.25v5.5q0 1.25 1.25 1.25H17q.074 0 .146.014q.073.015.141.043t.13.069q.061.041.113.094q.053.052.094.113t.069.13t.043.141t.014.146q0 .074-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014H6.5q-2.75 0-2.75-2.75V14q0-2.75 2.75-2.75h7.45q-.2-.459-.2-1v-5q0-2.5 2.5-2.5");
}

</style>
