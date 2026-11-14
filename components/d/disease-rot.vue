<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="heu-y0b3b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:disease-rot" /></template>
<style>
.heu-y0b3b {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M4.002 2.193L6.255 4.22q6.923-.644 11.005 4.17q4.155 4.901 2.982 12.721q-.011.071-.035.139t-.06.13q-.036.061-.084.115q-.047.054-.104.098t-.121.076q-.064.033-.133.052q-.069.02-.141.026t-.143-.001q-7.507-.79-11.364-5.256q-3.851-4.459-2.861-11.204L2.998 3.307q-.055-.049-.099-.108t-.076-.126t-.05-.138t-.022-.146q-.004-.073.007-.146q.01-.074.035-.143q.025-.07.062-.133q.038-.064.088-.119q.099-.111.234-.175t.284-.072t.289.042t.252.15M10.5 7.75q-2.25 0-2.25 2.25t2.25 2.25T12.75 10T10.5 7.75m.25 7Q10.75 17 13 17t2.25-2.25T13 12.5t-2.25 2.25");
}

</style>
