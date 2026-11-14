<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="flk-gjwhp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:display-plinth" /></template>
<style>
.flk-gjwhp {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M18.5 1.75h-13q-.932 0-1.591.659T3.25 4q0 2.25 2.25 2.25h.326q-.076.337-.076.75v10.5q0 .428.081.775q-1.581.197-1.581 1.975q0 2 2 2h11.5q2 0 2-2q0-1.778-1.581-1.975q.081-.347.081-.775V7q0-.413-.076-.75h.326q2.25 0 2.25-2.25T18.5 1.75M15.25 19q0 .074-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014t-.146-.014q-.073-.015-.141-.043t-.13-.069t-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141T13.75 19V5.5q0-.074.014-.146q.015-.073.043-.141t.069-.13q.041-.061.094-.113q.052-.053.113-.094t.13-.069t.141-.043t.146-.014t.146.014q.073.015.141.043t.13.069t.113.094q.053.052.094.113t.069.13t.043.141t.014.146z");
}

</style>
