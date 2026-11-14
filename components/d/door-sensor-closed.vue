<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ig0r7e1lq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:door-sensor-closed" /></template>
<style>
.ig0r7e1lq {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M7.5 3.25h1q1.76 0 3.005 1.245T12.75 7.5v9q0 1.76-1.245 3.005T8.5 20.75h-1q-1.76 0-3.005-1.245T3.25 16.5v-9q0-1.76 1.245-3.005T7.5 3.25m13 3.25q0-3.25-3.25-3.25T14 6.5v11q0 3.25 3.25 3.25t3.25-3.25zm-12.49.75H8q-.074 0-.146.014q-.073.015-.141.043t-.13.069q-.061.041-.113.094q-.053.052-.094.113t-.069.13t-.043.141T7.25 8t.014.146q.015.073.043.141t.069.13t.094.113q.052.053.113.094t.13.069t.141.043T8 8.75h.01q.074 0 .146-.014q.073-.015.141-.043t.13-.069t.113-.094q.053-.052.094-.113t.069-.13t.043-.141T8.76 8t-.014-.146q-.015-.073-.043-.141t-.069-.13q-.041-.061-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043t-.146-.014");
}

</style>
