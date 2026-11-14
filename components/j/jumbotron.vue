<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uibtrebqe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:jumbotron" /></template>
<style>
.uibtrebqe {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M18 1.75H6q-1.76 0-3.005 1.245T1.75 6v7q0 1.76 1.245 3.005T6 17.25h.25v4.25q0 .074.014.146q.015.073.043.141t.069.13q.041.061.094.113q.052.053.113.094t.13.069t.141.043t.146.014t.146-.014q.073-.015.141-.043t.13-.069q.061-.041.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146v-4.25h8.5v4.25q0 .074.014.146q.015.073.043.141t.069.13q.041.061.094.113q.052.053.113.094t.13.069t.141.043t.146.014q.074 0 .146-.014q.073-.015.141-.043t.13-.069q.061-.041.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146v-4.25H18q1.76 0 3.005-1.245T22.25 13V6q0-1.76-1.245-3.005T18 1.75m-5.423 5.301l.868.472q1.173.64 1.173 1.976t-1.173 1.976l-.868.473q-1.124.613-2.226-.041T9.25 9.973v-.946q0-1.281 1.101-1.935t2.226-.041");
}

</style>
