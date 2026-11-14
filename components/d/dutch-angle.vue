<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wmhvayb_x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:dutch-angle" /></template>
<style>
.wmhvayb_x {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M15.928 3.96L4.578 7.001q-3.26.873-2.386 4.133l1.747 6.52q.873 3.26 4.133 2.386l11.35-3.041q3.26-.873 2.386-4.133l-1.747-6.52q-.873-3.26-4.133-2.386m1.572 7.29q.074 0 .146.014q.073.015.141.043t.13.069q.061.041.113.094q.053.052.094.113t.069.13t.043.141t.014.146t-.014.146q-.015.073-.043.141t-.069.13t-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014h-11q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069q-.061-.041-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141T5.75 12t.014-.146q.015-.073.043-.141t.069-.13t.094-.113q.052-.053.113-.094t.13-.069t.141-.043t.146-.014z");
}

</style>
