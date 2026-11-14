<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kq3dxmpql"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:heat-transfer" /></template>
<style>
.kq3dxmpql {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M7.75 16.75v-9.5q0-3-3-3q-1.243 0-2.121.879q-.879.878-.879 2.121v9.5q0 3 3 3t3-3m8.5-9.5q0-3 3-3t3 3v9.5q0 3-3 3t-3-3zm-1.47 4.219L12.53 9.22q-.052-.053-.113-.094t-.13-.069t-.141-.043T12 9t-.146.014q-.073.015-.141.043t-.13.069t-.113.094q-.053.052-.094.113t-.069.13t-.043.141t-.014.146t.014.146q.015.073.043.141t.069.13t.094.113l.969.97H9.75q-.074 0-.146.014q-.073.015-.141.043t-.13.069t-.113.094q-.053.052-.094.113t-.069.13t-.043.141T9 12t.014.146q.015.073.043.141t.069.13t.094.113q.052.053.113.094t.13.069t.141.043t.146.014h2.689l-.969.97q-.053.052-.094.113t-.069.13t-.043.141t-.014.146t.014.146q.015.073.043.141t.069.13t.094.113q.052.053.113.094t.13.069t.141.043T12 15t.146-.014q.073-.015.141-.043t.13-.069t.113-.094l2.25-2.25q.106-.105.163-.243T15 12t-.057-.287t-.163-.243z");
}

</style>
