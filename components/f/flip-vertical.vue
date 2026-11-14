<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nnt1p-bxu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:flip-vertical" /></template>
<style>
.nnt1p-bxu {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M12.001 9.75H7.25q-2.5 0-2.5-2.5V5.735q0-1.368 1.152-2.106q1.153-.737 2.395-.164l4.615 2.13q1.589.735 1.214 2.444T12.001 9.75M3 12.75h18q.074 0 .146-.014q.073-.015.141-.043t.13-.069q.061-.041.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146t-.014-.146q-.015-.073-.043-.141t-.069-.13t-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043T21 11.25H3q-.074 0-.146.014q-.073.015-.141.043t-.13.069t-.113.094q-.053.052-.094.113t-.069.13t-.043.141q-.014.072-.014.146t.014.146q.015.073.043.141t.069.13t.094.113q.052.053.113.094t.13.069t.141.043t.146.014m11.126 3.211q-.375-1.709-2.125-1.711H7.25q-2.5 0-2.5 2.5v1.515q0 1.368 1.152 2.106q1.153.737 2.395.164l4.615-2.13q1.589-.735 1.214-2.444");
}

</style>
