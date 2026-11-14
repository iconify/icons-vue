<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jgp1dubpu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:concealer" /></template>
<style>
.jgp1dubpu {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M9.25 9.364q2.25.505 2.25 3.261v5.25q0 3.375-3.375 3.375h-2.25q-3.375 0-3.375-3.375v-5.25q0-2.756 2.25-3.261V5q0-2.25 2.25-2.25T9.25 5zm-1.5-.114V5q0-.75-.75-.75T6.25 5v4.25zm5 11.25V11q0-1.76 1.245-3.005T17 6.75t3.005 1.245T21.25 11v9.5q0 .074-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014h-7q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069t-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141t-.014-.146");
}

</style>
