<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ptecu3btt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:image-landscape" /></template>
<style>
.ptecu3btt {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M5.5 5.25h13q1.76 0 3.005 1.245T22.75 9.5v5q0 1.76-1.245 3.005T18.5 18.75h-3.998q.148 0 .286-.057t.242-.163q.053-.052.094-.113t.069-.13t.043-.141t.014-.146t-.014-.146q-.015-.073-.043-.141t-.069-.13q-.041-.061-.094-.113l-7.5-7.5q-.105-.106-.243-.163T7 9.75t-.287.057t-.243.163l-5 5q-.108.107-.165.248q-.055-.348-.055-.718v-5q0-1.76 1.245-3.005T5.5 5.25M14.25 10q0 2.25 2.25 2.25T18.75 10T16.5 7.75T14.25 10m-.28 8.53q.105.106.242.163q.138.057.286.057H5.5q-1.76 0-3.005-1.245q-.636-.636-.947-1.407q.097.074.213.113q.117.039.239.039q.149 0 .287-.057t.243-.163L7 11.561z");
}

</style>
