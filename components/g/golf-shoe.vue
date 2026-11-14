<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ejejyeblb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:golf-shoe" /></template>
<style>
.ejejyeblb {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M2.75 16V6.5q0-.074.014-.146q.015-.073.043-.141t.069-.13q.041-.061.094-.113q.052-.053.113-.094t.13-.069t.141-.043t.146-.014h5q.067 0 .133.012t.129.035t.121.058t.108.078t.093.097q.042.052.075.111t.053.123q.021.063.03.13q.583 4.078 6.851 4.862l.03.004q5.627.938 5.627 4.74q0 .074-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014h-.826q-.337 1.5-2.174 1.5t-2.174-1.5h-1.652q-.337 1.5-2.174 1.5t-2.174-1.5H8.174q-.337 1.5-2.174 1.5t-2.174-1.5H3.5q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069t-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141T2.75 16");
}

</style>
