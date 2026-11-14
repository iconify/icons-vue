<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mugopjboe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:audio-interface" /></template>
<style>
.mugopjboe {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M18 6.75H6q-1.76 0-3.005 1.245T1.75 11v2q0 1.76 1.245 3.005T6 17.25h12q1.76 0 3.005-1.245T22.25 13v-2q0-1.76-1.245-3.005T18 6.75M4.25 12q0-2.75 2.75-2.75T9.75 12T7 14.75T4.25 12M13 9.25q2.75 0 2.75 2.75T13 14.75T10.25 12T13 9.25m5.51 2q.074 0 .146.014q.073.015.141.043t.13.069t.113.094q.053.052.094.113t.069.13t.043.141q.014.072.014.146t-.014.146q-.015.073-.043.141t-.069.13t-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014h-.01q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069q-.061-.041-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141T17.75 12t.014-.146q.015-.073.043-.141t.069-.13t.094-.113q.052-.053.113-.094t.13-.069t.141-.043t.146-.014z");
}

</style>
