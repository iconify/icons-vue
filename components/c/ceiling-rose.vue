<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h9edxybak"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:ceiling-rose" /></template>
<style>
.h9edxybak {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M21 2.75H3q-.074 0-.146.014q-.073.015-.141.043t-.13.069t-.113.094q-.053.052-.094.113t-.069.13t-.043.141q-.014.072-.014.146t.014.146q.015.073.043.141t.069.13t.094.113q.052.053.113.094t.13.069t.141.043T3 4.25h3.35q.328 1.174 1.729 2.014q1.365.82 3.171.958v4.082q-1.491.219-2.609 1.337Q7.25 14.032 7.25 16t1.391 3.359T12 20.75t3.359-1.391T16.75 16t-1.391-3.359q-1.118-1.118-2.609-1.337V7.222q1.806-.138 3.171-.958q1.401-.84 1.729-2.014H21q.074 0 .146-.014q.073-.015.141-.043t.13-.069q.061-.041.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146t-.014-.146q-.015-.073-.043-.141t-.069-.13t-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043T21 2.75m-9 3q-3.47 0-4.107-1.5h8.214Q15.47 5.75 12 5.75");
}

</style>
