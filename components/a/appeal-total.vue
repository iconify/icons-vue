<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rl0x2fbrc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:appeal-total" /></template>
<style>
.rl0x2fbrc {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M16.5 3.25h-8Q5.75 3.25 5.75 6q0 .8.233 1.367Q4.25 7.817 4.25 10q0 2.459 2.199 2.719Q6.25 13.26 6.25 14q0 2.75 2.75 2.75h8q2.75 0 2.75-2.75q0-2.459-2.199-2.719q.199-.541.199-1.281q0-.8-.233-1.367Q19.25 8.183 19.25 6q0-2.75-2.75-2.75M4 19.25h16q.074 0 .146.014q.073.015.141.043t.13.069q.061.041.113.094q.053.052.094.113t.069.13t.043.141t.014.146q0 .074-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014H4q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069t-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141T3.25 20t.014-.146q.015-.073.043-.141t.069-.13q.041-.061.094-.113q.052-.053.113-.094t.13-.069t.141-.043T4 19.25");
}

</style>
