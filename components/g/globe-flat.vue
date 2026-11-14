<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q0udfllnp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:globe-flat" /></template>
<style>
.q0udfllnp {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M6 4.25h6q-2.273 0-3.813 2.395q-1.261 1.962-1.415 4.605H2.5q-.074 0-.146.014q-.073.015-.141.043t-.13.069t-.113.094q-.053.052-.094.113t-.069.13t-.043.141q-.014.072-.014.146V8.5q0-1.76 1.245-3.005T6 4.25m.772 8.5H2.5q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069t-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141Q1.75 12.074 1.75 12v3.5q0 1.76 1.245 3.005T6 19.75h12q1.76 0 3.005-1.245T22.25 15.5v-7q0-1.76-1.245-3.005T18 4.25h-6q2.273 0 3.813 2.395q1.261 1.962 1.415 4.605H21.5q.074 0 .146.014q.073.015.141.043t.13.069q.061.041.113.094q.053.052.094.113t.069.13t.043.141t.014.146t-.014.146q-.015.073-.043.141t-.069.13t-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014h-4.272q-.154 2.643-1.415 4.605Q14.273 19.75 12 19.75t-3.813-2.395q-1.261-1.962-1.415-4.605");
}

</style>
