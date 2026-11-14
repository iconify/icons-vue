<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rk9fneq_b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:category-sustainable" /></template>
<style>
.rk9fneq_b {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M12.75 14q0-1.219-.202-2.258Q21.25 11.487 21.25 3q0-.074-.014-.146q-.015-.073-.043-.141t-.069-.13t-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043t-.146-.014q-8.066 0-9.098 6.653Q9.218 5.75 3.5 5.75q-.074 0-.146.014q-.073.015-.141.043t-.13.069t-.113.094q-.053.052-.094.113t-.069.13t-.043.141q-.014.072-.014.146q0 7.908 8.5 8.236v1.529q-6.002.241-7.931 4.421q-.069.149-.069.314q0 .074.014.146q.015.073.043.141t.069.13q.041.061.094.113q.052.053.113.094t.13.069t.141.043t.146.014h16q.165 0 .314-.069q.136-.063.237-.172q.101-.11.153-.25t.045-.289t-.068-.284q-1.929-4.18-7.931-4.421z");
}

</style>
