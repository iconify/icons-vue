<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b8zpy0bxf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:bus-stop-sign" /></template>
<style>
.b8zpy0bxf {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M9.375 1.75h5.25q2.123 0 3.624 1.501t1.501 3.624v3.75q0 2.123-1.501 3.624t-3.624 1.501H12.75v5H15q.074 0 .146.014q.073.015.141.043t.13.069t.113.094q.053.052.094.113t.069.13t.043.141t.014.146t-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014H9q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069t-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141t-.014-.146t.014-.146q.015-.073.043-.141t.069-.13q.041-.061.094-.113q.052-.053.113-.094t.13-.069t.141-.043T9 20.75h2.25v-5H9.375q-2.123 0-3.624-1.501T4.25 10.625v-3.75q0-2.123 1.501-3.624T9.375 1.75m3.5 3h-1.75q-3.375 0-3.375 3.375v1.25q0 1.398.989 2.386q.988.989 2.386.989h1.75q1.398 0 2.386-.989q.989-.988.989-2.386v-1.25q0-3.375-3.375-3.375");
}

</style>
