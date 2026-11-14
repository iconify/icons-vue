<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="epz6iacak"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:layout-split-vertical" /></template>
<style>
.epz6iacak {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M12 3.25H6q-1.76 0-3.005 1.245T1.75 7.5v9q0 1.76 1.245 3.005T6 20.75h12q1.76 0 3.005-1.245T22.25 16.5v-9q0-1.76-1.245-3.005T18 3.25zm0 0q.074 0 .146.014q.073.015.141.043t.13.069t.113.094q.053.052.094.113t.069.13t.043.141t.014.146v16q0 .074-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014t-.146-.014q-.073-.015-.141-.043t-.13-.069t-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141T11.25 20V4q0-.074.014-.146q.015-.073.043-.141t.069-.13t.094-.113q.052-.053.113-.094t.13-.069t.141-.043q.072-.014.146-.014");
}

</style>
