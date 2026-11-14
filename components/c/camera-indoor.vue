<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dickng42m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:camera-indoor" /></template>
<style>
.dickng42m {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("m3.506 9.936l8-7q.051-.045.109-.08q.058-.034.121-.058t.13-.036T12 2.75t.134.012t.13.036t.121.058q.058.035.109.08l8 7q.122.106.189.254t.067.31v10q0 .074-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014H4q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069t-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141t-.014-.146v-10q0-.162.067-.31t.189-.254M12 10.25q-4 0-4 4t4 4t4-4q0-1.657-1.172-2.828Q13.657 10.25 12 10.25");
}

</style>
