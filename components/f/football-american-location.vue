<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ahllf-bif"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:football-american-location" /></template>
<style>
.ahllf-bif {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M6.532 6.532Q2.25 10.814 2.25 17.5q0 .074.014.146q.015.073.043.141t.069.13q.041.061.094.113q.052.053.113.094t.13.069t.141.043t.146.014q6.686 0 10.968-4.282T18.25 3q0-.074-.014-.146q-.015-.073-.043-.141t-.069-.13t-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043t-.146-.014q-6.686 0-10.968 4.282M17.97 22.03q-3.22-3.219-3.22-5.03q0-3.75 3.75-3.75T22.25 17q0 1.811-3.22 5.03q-.052.053-.113.094t-.13.069t-.141.043t-.146.014q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069q-.061-.041-.113-.094M20.75 17q0 1.07-2.25 3.427Q16.25 18.07 16.25 17q0-2.25 2.25-2.25T20.75 17");
}

</style>
