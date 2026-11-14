<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mjw5_lgqi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:bunker" /></template>
<style>
.mjw5_lgqi {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M2.774 16.25q.232-3.545 2.671-6.127Q8.157 7.253 12 7.253t6.555 2.87q2.439 2.582 2.671 6.127h.274q.074 0 .146.014q.073.015.141.043t.13.069q.061.041.113.094q.053.052.094.113t.069.13t.043.141t.014.146q0 .074-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014h-19q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069t-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141T1.75 17t.014-.146q.015-.073.043-.141t.069-.13q.041-.061.094-.113q.052-.053.113-.094t.13-.069t.141-.043t.146-.014zm7.476 0h3.5V14q0-1.75-1.75-1.75T10.25 14zm5 0h4.472q-.227-2.948-2.258-5.097q-2.267-2.4-5.464-2.4t-5.464 2.4q-2.031 2.149-2.258 5.097H8.75V14q0-3.25 3.25-3.25T15.25 14z");
}

</style>
