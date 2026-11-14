<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d729jqbdu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:layout-panel-left" /></template>
<style>
.d729jqbdu {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M9 2.25H6.5q-1.76 0-3.005 1.245T2.25 6.5v11q0 1.76 1.245 3.005T6.5 21.75h11q1.76 0 3.005-1.245T21.75 17.5v-11q0-1.76-1.245-3.005T17.5 2.25zm0 0q.074 0 .146.014q.073.015.141.043t.13.069t.113.094q.053.052.094.113t.069.13t.043.141T9.75 3v18q0 .074-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113q-.052.053-.113.094t-.13.069t-.141.043T9 21.75t-.146-.014q-.073-.015-.141-.043t-.13-.069t-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141T8.25 21V3q0-.074.014-.146q.015-.073.043-.141t.069-.13t.094-.113q.052-.053.113-.094t.13-.069t.141-.043Q8.926 2.25 9 2.25");
}

</style>
