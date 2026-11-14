<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hlijvdbul"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:learning-objectives" /></template>
<style>
.hlijvdbul {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M1.75 12q0-4.246 3.002-7.248T12 1.75t7.248 3.002T22.25 12t-3.002 7.248T12 22.25t-7.248-3.002T1.75 12m4 0q0-2.589 1.831-4.419Q9.411 5.75 12 5.75t4.419 1.831T18.25 12t-1.831 4.419Q14.589 18.25 12 18.25t-4.419-1.831Q5.75 14.589 5.75 12m1.5 0q0 1.968 1.391 3.359T12 16.75t3.359-1.391T16.75 12t-1.391-3.359T12 7.25T8.641 8.641T7.25 12m4.76-.75H12q-.074 0-.146.014q-.073.015-.141.043t-.13.069t-.113.094q-.053.052-.094.113t-.069.13t-.043.141t-.014.146t.014.146q.015.073.043.141t.069.13t.094.113q.052.053.113.094t.13.069t.141.043t.146.014h.01q.074 0 .146-.014q.073-.015.141-.043t.13-.069t.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146t-.014-.146q-.015-.073-.043-.141t-.069-.13t-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043t-.146-.014");
}

</style>
