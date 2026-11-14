<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v36cj8bcv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:declutter" /></template>
<style>
.v36cj8bcv {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M12 3.25H9.25q-2.5 0-2.5 2.5v5q0 .541.2 1h-2.2q-2.5 0-2.5 2.5v5q0 1.036.732 1.768t1.768.732h5.5q1.023 0 1.75-.715q.727.715 1.75.715h5.5q1.036 0 1.768-.732t.732-1.768v-5q0-1.036-.732-1.768t-1.768-.732h-2.2q.2-.459.2-1v-5q0-2.5-2.5-2.5zm0 0q.074 0 .146.014q.073.015.141.043t.13.069t.113.094q.053.052.094.113t.069.13t.043.141t.014.146v3q0 .074-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113q-.052.053-.113.094t-.13.069t-.141.043T12 7.75t-.146-.014q-.073-.015-.141-.043t-.13-.069t-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141T11.25 7V4q0-.074.014-.146q.015-.073.043-.141t.069-.13t.094-.113q.052-.053.113-.094t.13-.069t.141-.043q.072-.014.146-.014");
}

</style>
