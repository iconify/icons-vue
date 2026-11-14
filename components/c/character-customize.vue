<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wnqerq_bm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:character-customize" /></template>
<style>
.wnqerq_bm {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M5.75 7q0-1.968 1.391-3.359T10.5 2.25t3.359 1.391T15.25 7t-1.391 3.359T10.5 11.75t-3.359-1.391T5.75 7m7 11.75v2.5H4q-1.75 0-1.75-1.75q0-2.798 2.468-4.577q2.32-1.673 5.782-1.673q3.23 0 5.466 1.456l-2.63 2.63q-.14.139-.249.303t-.185.346q-.075.182-.114.375q-.038.193-.038.39m1.25 2.5v-2.5q0-.149.057-.287t.163-.243l4.75-4.75q.052-.053.113-.094t.13-.069t.141-.043t.146-.014t.146.014q.073.015.141.043t.13.069q.061.041.113.094l2.5 2.5q.053.052.094.113t.069.13t.043.141t.014.146q0 .074-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113l-4.75 4.75q-.105.106-.243.163T17.25 22h-2.5q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069t-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141T14 21.25m2.939-.75l4-4l-1.439-1.439l-4 4V20.5z");
}

</style>
