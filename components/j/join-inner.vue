<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fhji9abmx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:join-inner" /></template>
<style>
.fhji9abmx {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M6 1.75h5.5q1.76 0 3.005 1.245T15.75 6v2.25H18q1.76 0 3.005 1.245T22.25 12.5V18q0 1.76-1.245 3.005T18 22.25h-5.5q-1.76 0-3.005-1.245T8.25 18v-2.25H6q-1.76 0-3.005-1.245T1.75 11.5V6q0-1.76 1.245-3.005T6 1.75M8.25 11v4q0 .074.014.146q.015.073.043.141t.069.13t.094.113q.052.053.113.094t.13.069t.141.043t.146.014h4q2.75 0 2.75-2.75V9q0-.074-.014-.146q-.015-.073-.043-.141t-.069-.13t-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043T15 8.25h-4q-2.75 0-2.75 2.75");
}

</style>
