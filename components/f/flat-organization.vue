<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zfq9ei0ik"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:flat-organization" /></template>
<style>
.zfq9ei0ik {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M7.518 9.982Q6.786 9.25 5.75 9.25v-3h5.5v3q-2.5 0-2.5 2.5v3.5q0 2.5 2.5 2.5h1.5q1.036 0 1.768-.732t.732-1.768v-3.5q0-1.036-.732-1.768T12.75 9.25v-3h5.5v3q-2.5 0-2.5 2.5v3.5q0 2.5 2.5 2.5h1.5q1.036 0 1.768-.732t.732-1.768v-3.5q0-1.036-.732-1.768T19.75 9.25V5.5q0-.074-.014-.146q-.015-.073-.043-.141t-.069-.13q-.041-.061-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043T19 4.75H5q-.074 0-.146.014q-.073.015-.141.043t-.13.069q-.061.041-.113.094q-.053.052-.094.113t-.069.13t-.043.141t-.014.146v3.75q-1.036 0-1.768.732T1.75 11.75v3.5q0 2.5 2.5 2.5h1.5q1.036 0 1.768-.732t.732-1.768v-3.5q0-1.036-.732-1.768");
}

</style>
