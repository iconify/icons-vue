<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ba3ot7p2e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:bushing" /></template>
<style>
.ba3ot7p2e {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M10 3.75h4q1.76 0 3.005 1.245T18.25 8v1.25h3.25q.074 0 .146.014q.073.015.141.043t.13.069q.061.041.113.094q.053.052.094.113t.069.13t.043.141t.014.146v4q0 .074-.014.146q-.015.073-.043.141t-.069.13t-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014h-3.25V16q0 1.76-1.245 3.005T14 20.25h-4q-1.76 0-3.005-1.245T5.75 16v-1.25H2.5q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069t-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141Q1.75 14.074 1.75 14v-4q0-.074.014-.146q.015-.073.043-.141t.069-.13t.094-.113q.052-.053.113-.094t.13-.069t.141-.043t.146-.014h3.25V8q0-1.76 1.245-3.005T10 3.75m-4.25 7h-2.5v2.5h2.5zm15 0h-2.5v2.5h2.5z");
}

</style>
