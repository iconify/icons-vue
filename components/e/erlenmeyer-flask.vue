<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s-hybdcbg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:erlenmeyer-flask" /></template>
<style>
.s-hybdcbg {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M8.75 3.75v4.819l-4.917 9.589l-.009.017q-.627 1.306.029 2.423Q4.529 21.75 6 21.75h12q1.471 0 2.147-1.152q.656-1.117.029-2.423l-.009-.017l-4.917-9.589V3.75H16q.074 0 .146-.014q.073-.015.141-.043t.13-.069q.061-.041.113-.094q.053-.052.094-.113t.069-.13t.043-.141T16.75 3t-.014-.146q-.015-.073-.043-.141t-.069-.13t-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043T16 2.25H8q-.074 0-.146.014q-.073.015-.141.043t-.13.069q-.061.041-.113.094q-.053.052-.094.113t-.069.13t-.043.141T7.25 3t.014.146q.015.073.043.141t.069.13t.094.113q.052.053.113.094t.13.069t.141.043q.072.014.146.014zm1.5 0h3.5v5q0 .181.083.342l2.645 5.158H7.522l2.645-5.158q.083-.161.083-.342zm6.979 11.964l1.599 3.119q.275.58.025 1.006q-.241.411-.853.411H6q-.612 0-.853-.411q-.25-.426.025-1.006l1.599-3.119q.112.036.229.036h10q.117 0 .229-.036");
}

</style>
