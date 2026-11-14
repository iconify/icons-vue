<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q_6lp_bjr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:ink-cartridge" /></template>
<style>
.q_6lp_bjr {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M7.625 1.75h8.75q3.375 0 3.375 3.375v11.75q0 3.375-3.375 3.375H14.75v1.25q0 .074-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014h-4q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069t-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141t-.014-.146v-1.25H7.625q-3.375 0-3.375-3.375V5.125q0-3.375 3.375-3.375m4.944 5.262q-.037-.044-.081-.081q-.113-.098-.255-.144t-.291-.035t-.281.079t-.23.181Q8.25 10.723 8.25 13q0 3.75 3.75 3.75T15.75 13q0-2.277-3.181-5.988M10.75 20.25v.5h2.5v-.5z");
}

</style>
