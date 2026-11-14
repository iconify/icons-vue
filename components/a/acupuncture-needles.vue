<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jqgwysdhl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:acupuncture-needles" /></template>
<style>
.jqgwysdhl {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M15.75 5.5q0-2.75 2.75-2.75t2.75 2.75t-2.75 2.75q-.845 0-1.43-.259L6.53 18.53q-.105.106-.243.163T6 18.75t-.287-.057t-.243-.163q-.053-.052-.094-.113t-.069-.13t-.043-.141T5.25 18q0-.074.014-.146q.015-.073.043-.141t.069-.13q.041-.061.094-.113L16.009 6.93q-.259-.585-.259-1.43m-11.99 14h-.01q-.074 0-.146.014q-.073.015-.141.043t-.13.069t-.113.094q-.053.052-.094.113t-.069.13t-.043.141T3 20.25t.014.146q.015.073.043.141t.069.13q.041.061.094.113q.052.053.113.094t.13.069t.141.043t.146.014h.01q.074 0 .146-.014q.073-.015.141-.043t.13-.069q.061-.041.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146q0-.074-.014-.146q-.015-.073-.043-.141t-.069-.13q-.041-.061-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043t-.146-.014");
}

</style>
