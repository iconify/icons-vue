<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g41vymb3l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:adoption" /></template>
<style>
.g41vymb3l {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("m4.104 9.413l6.25-5.468q1.646-1.44 3.292-.001l1.604 1.404V4q0-.074.014-.146q.015-.073.043-.141t.069-.13t.094-.113q.052-.053.113-.094t.13-.069t.141-.043q.072-.014.146-.014h2q.074 0 .146.014q.073.015.141.043t.13.069q.061.041.113.094q.053.052.094.113t.069.13t.043.141t.014.146v4.41l1.146 1.003q.854.746.854 1.881v7.456q0 2.5-2.5 2.5H5.75q-2.5 0-2.5-2.5v-7.456q0-1.135.854-1.881M17.25 7.097V4.75h-.5v1.91zM11.47 18.53q.052.053.113.094t.13.069t.141.043t.146.014t.146-.014q.073-.015.141-.043t.13-.069t.113-.094l3-3q.083-.082.136-.186q1.013-1.961-.683-3.374q-1.472-1.227-2.983-.371q-1.511-.856-2.983.371q-1.696 1.413-.683 3.374q.053.104.136.186z");
}

</style>
