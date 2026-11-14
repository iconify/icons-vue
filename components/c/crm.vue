<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qupe_pqqm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:crm" /></template>
<style>
.qupe_pqqm {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M19.25 14.75v.75q0 2.25-2.25 2.25h-.761q-.182 3-3.364 3h-7.75q-3.375 0-3.375-3.375v-4.75q0-3.182 3-3.364V8.5q0-2.25 2.25-2.25h.75V5.5q0-2.25 2.25-2.25h10q2.25 0 2.25 2.25v7q0 .932-.659 1.591T20 14.75zm-10-8.5V5.5q0-.75.75-.75h10q.75 0 .75.75v7q0 .75-.75.75h-.75V8.5q0-2.25-2.25-2.25zM17 7.75H7q-.75 0-.75.75v.75h6.625q3.375 0 3.375 3.375v3.625H17q.75 0 .75-.75v-7q0-.75-.75-.75m-6.5 6.5h-5q-.074 0-.146.014q-.073.015-.141.043t-.13.069q-.061.041-.113.094q-.053.052-.094.113t-.069.13t-.043.141T4.75 15t.014.146q.015.073.043.141t.069.13t.094.113q.052.053.113.094t.13.069t.141.043t.146.014h5q.074 0 .146-.014q.073-.015.141-.043t.13-.069t.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146t-.014-.146q-.015-.073-.043-.141t-.069-.13t-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043t-.146-.014");
}

</style>
