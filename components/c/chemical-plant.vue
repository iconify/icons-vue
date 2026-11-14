<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mpn81mofn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:chemical-plant" /></template>
<style>
.mpn81mofn {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M21.5 21.75h-19q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069t-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141T1.75 21t.014-.146q.015-.073.043-.141t.069-.13q.041-.061.094-.113q.052-.053.113-.094t.13-.069t.141-.043t.146-.014h.25V7q0-1.76 1.245-3.005T7 2.75t3.005 1.245T11.25 7v6.25h1.5V10q0-1.76 1.245-3.005T17 5.75t3.005 1.245T21.25 10v10.25h.25q.074 0 .146.014q.073.015.141.043t.13.069q.061.041.113.094q.053.052.094.113t.069.13t.043.141t.014.146q0 .074-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014m-8.75-7h-1.5v5.5h1.5zm-3-.75V7q0-2.75-2.75-2.75T4.25 7v13.25h5.5zm10 6.25V10q0-2.75-2.75-2.75T14.25 10v10.25z");
}

</style>
