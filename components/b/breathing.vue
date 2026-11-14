<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ek1fzizqw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:breathing" /></template>
<style>
.ek1fzizqw {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M12.75 10V3q0-.074-.014-.146q-.015-.073-.043-.141t-.069-.13t-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043Q12.074 2.25 12 2.25t-.146.014q-.073.015-.141.043t-.13.069t-.113.094q-.053.052-.094.113t-.069.13t-.043.141T11.25 3v7q0 .074.014.146q.015.073.043.141t.069.13t.094.113q.052.053.113.094t.13.069t.141.043t.146.014t.146-.014q.073-.015.141-.043t.13-.069t.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146m-2.281-2.086q.065.053.118.119t.089.142q.037.076.055.158q.019.083.019.167v8q0 4.25-4 4.25t-4-6.25q0-4.298 2.591-6.395q2.667-2.159 5.128-.191m8.19.191q-2.667-2.159-5.128-.191q-.065.053-.118.119t-.089.142q-.037.076-.055.158q-.019.083-.019.167v8q0 4.25 4 4.25t4-6.25q0-4.298-2.591-6.395");
}

</style>
