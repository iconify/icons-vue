<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pr8cwbb7o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:catamaran-sail" /></template>
<style>
.pr8cwbb7o {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M11.25 2.5v13.25H3q-.074 0-.146.014q-.073.015-.141.043t-.13.069t-.113.094q-.053.052-.094.113t-.069.13t-.043.141t-.014.146q0 .116.035.227t.103.206t.16.165t.202.109V18q0 3 3 3t3-3v-.75h6.5V18q0 3 3 3q1.243 0 2.121-.879q.879-.878.879-2.121v-.793q.11-.039.202-.109t.16-.165t.103-.206t.035-.227q0-.074-.014-.146q-.015-.073-.043-.141t-.069-.13q-.041-.061-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043T21 15.75h-8.25v-1.5h5.75q.205 0 .382-.104q.128-.076.218-.195q.089-.12.126-.264t.017-.292t-.097-.277l-6.5-11q-.05-.084-.12-.152q-.069-.069-.154-.117q-.085-.049-.18-.074T12 1.75q-.074 0-.146.014q-.073.015-.141.043t-.13.069t-.113.094q-.053.052-.094.113t-.069.13t-.043.141t-.014.146m1.5 10.25h4.436L12.75 5.243zm-5.5 4.5h-3V18q0 1.5 1.5 1.5t1.5-1.5zm9.5.75v-.75h3V18q0 .621-.439 1.061q-.44.439-1.061.439q-1.5 0-1.5-1.5");
}

</style>
