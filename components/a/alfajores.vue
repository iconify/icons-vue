<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aqyg7r47z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:alfajores" /></template>
<style>
.aqyg7r47z {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M12 5.375q-9.75 0-9.75 4.125q0 .074.014.146q.015.073.043.141t.069.13t.094.113q.052.053.113.094t.13.069t.141.043t.146.014h.478Q3 11.11 3 12t.478 1.75H3q-.074 0-.146.014q-.073.015-.141.043t-.13.069t-.113.094q-.053.052-.094.113t-.069.13t-.043.141q-.014.072-.014.146q0 3.75 9.75 3.75t9.75-3.75q0-.074-.014-.146q-.015-.073-.043-.141t-.069-.13t-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043T21 13.75h-.478Q21 12.89 21 12t-.478-1.75H21q.074 0 .146-.014q.073-.015.141-.043t.13-.069q.061-.041.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146q0-4.125-9.75-4.125m6.677 4.875q1.555 1.75 0 3.5H5.323q-1.555-1.75 0-3.5z");
}

</style>
