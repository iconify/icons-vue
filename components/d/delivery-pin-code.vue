<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wnx5xnbwb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:delivery-pin-code" /></template>
<style>
.wnx5xnbwb {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M16 1.75H6q-1.76 0-3.005 1.245T1.75 6v10q0 1.76 1.245 3.005T6 20.25h6.792q-.042-.354-.042-.75v-3q0-3.75 3.75-3.75h3q.396 0 .75.042V6q0-1.76-1.245-3.005T16 1.75m4.25 5.75q0 .074-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014h-17q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069t-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141T1.75 7.5t.014-.146q.015-.073.043-.141t.069-.13q.041-.061.094-.113q.052-.053.113-.094t.13-.069t.141-.043t.146-.014h17q.074 0 .146.014q.073.015.141.043t.13.069q.061.041.113.094q.053.052.094.113t.069.13t.043.141t.014.146m-6.25 9q0-2.5 2.5-2.5h3q2.5 0 2.5 2.5v3q0 2.5-2.5 2.5h-3Q14 22 14 19.5zm3.25-1v1.75H15.5v-.75q0-1 1-1zm3.25 1q0-1-1-1h-.75v1.75h1.75zm-3.25 2.25H15.5v.75q0 1 1 1h.75zm3.25 0h-1.75v1.75h.75q1 0 1-1z");
}

</style>
