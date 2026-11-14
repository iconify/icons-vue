<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cg5s0xuez"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:dept-household-sign" /></template>
<style>
.cg5s0xuez {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M7.75 7.75V3q0-.074-.014-.146q-.015-.073-.043-.141t-.069-.13t-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043Q7.074 2.25 7 2.25t-.146.014t-.141.043t-.13.069t-.113.094q-.053.052-.094.113t-.069.13t-.043.141T6.25 3v4.756q-1.6.083-2.755 1.239Q2.25 10.24 2.25 12v5q0 1.76 1.245 3.005T6.5 21.25h11q1.76 0 3.005-1.245T21.75 17v-5q0-1.76-1.245-3.005q-1.155-1.156-2.755-1.239V3q0-.074-.014-.146q-.015-.073-.043-.141t-.069-.13t-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043T17 2.25t-.146.014q-.073.015-.141.043t-.13.069q-.061.041-.113.094q-.053.052-.094.113t-.069.13t-.043.141T16.25 3v4.75zm.719 5.755l2-1.857q1.531-1.422 3.062.001l2 1.856q.719.668.719 1.649V16.5q0 .932-.659 1.591T14 18.75h-4q-2.25 0-2.25-2.25v-1.346q0-.981.719-1.648z");
}

</style>
