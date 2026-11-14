<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ws6xu2b3v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:lockout-hasp" /></template>
<style>
.ws6xu2b3v {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M7.25 7.5v3.256q-1.6.083-2.755 1.239Q3.25 13.24 3.25 15v1.5q0 1.76 1.245 3.005T7.5 20.75h9q1.76 0 3.005-1.245T20.75 16.5V15q0-1.76-1.245-3.005T16.5 10.75H8.75V7.5q0-3.25 3.25-3.25t3.25 3.25V9q0 .074.014.146q.015.073.043.141t.069.13t.094.113q.052.053.113.094t.13.069t.141.043t.146.014t.146-.014q.073-.015.141-.043t.13-.069q.061-.041.113-.094q.053-.052.094-.113t.069-.13t.043-.141T16.75 9V7.5q0-1.968-1.391-3.359T12 2.75T8.641 4.141T7.25 7.5m-1.5 8.25q0-2 2-2t2 2t-2 2t-2-2m6.25-2q2 0 2 2t-2 2t-2-2t2-2m2.25 2q0-2 2-2t2 2t-2 2t-2-2");
}

</style>
