<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o73eq-w1s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:business-travel-bag" /></template>
<style>
.o73eq-w1s {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M16.505 7.495q-.676-.677-1.505-.986V2.5q0-.074-.014-.146q-.015-.073-.043-.141t-.069-.13t-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043q-.072-.014-.146-.014h-4.5q-.074 0-.146.014q-.073.015-.141.043t-.13.069t-.113.094q-.053.052-.094.113t-.069.13t-.043.141T9 2.5v4.009q-.829.309-1.505.986Q6.25 8.74 6.25 10.5V16q0 1.76 1.245 3.005q.109.109.222.209q-.067.057-.132.121Q7 19.921 7 20.749v.002q0 .828.585 1.414q.586.586 1.415.586t1.415-.586t.585-1.416q0-.261-.058-.499h2.094q-.036.232-.036.5q0 2 2 2t2-2q0-1.122-.63-1.615q.068-.063.135-.13Q17.75 17.76 17.75 16v-5.5q0-1.76-1.245-3.005M13.5 6.25h-3v-3h3z");
}

</style>
