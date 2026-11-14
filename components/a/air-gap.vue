<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q099uibau"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:air-gap" /></template>
<style>
.q099uibau {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M5.875 7.25h-.75q-3.375 0-3.375 3.375v2.75q0 3.375 3.375 3.375h.75q3.375 0 3.375-3.375v-.625H10q.074 0 .146-.014q.073-.015.141-.043t.13-.069t.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146t-.014-.146q-.015-.073-.043-.141t-.069-.13t-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043T10 11.25h-.75v-.625q0-3.375-3.375-3.375m12.25 0h.75q3.375 0 3.375 3.375v2.75q0 3.375-3.375 3.375h-.75q-3.375 0-3.375-3.375v-.625H14q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069t-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141T13.25 12t.014-.146q.015-.073.043-.141t.069-.13t.094-.113q.052-.053.113-.094t.13-.069t.141-.043t.146-.014h.75v-.625q0-3.375 3.375-3.375");
}

</style>
