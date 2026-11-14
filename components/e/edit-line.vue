<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tlem0sb2w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:edit-line" /></template>
<style>
.tlem0sb2w {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("m18.834 3.46l-.707-.708h-.001q-1.59-1.591-3.181 0L7.841 9.856q-.482.481-.615 1.149l-.264 1.323q-.205 1.024.533 1.763q.739.738 1.763.533l1.322-.264q.669-.133 1.15-.616l7.103-7.103q1.591-1.59.001-3.181M20.5 19.75h-17q-.074 0-.146.014q-.073.015-.141.043t-.13.069t-.113.094q-.053.052-.094.113t-.069.13t-.043.141t-.014.146q0 .074.014.146q.015.073.043.141t.069.13q.041.061.094.113q.052.053.113.094t.13.069t.141.043t.146.014h17q.074 0 .146-.014q.073-.015.141-.043t.13-.069q.061-.041.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146q0-.074-.014-.146q-.015-.073-.043-.141t-.069-.13q-.041-.061-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043t-.146-.014");
}

</style>
