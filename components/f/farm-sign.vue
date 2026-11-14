<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qjb97sbin"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:farm-sign" /></template>
<style>
.qjb97sbin {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M12.75 2.5v1.25h5.06q1.035 0 1.709.786l1.713 2q1.255 1.464.001 2.928l-1.715 2q-.673.786-1.708.786h-5.06v9.25q0 .074-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014t-.146-.014q-.073-.015-.141-.043t-.13-.069t-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141t-.014-.146v-9.25H6.19q-1.035 0-1.709-.786l-1.713-2Q1.513 8 2.767 6.536h.001l1.714-2q.673-.786 1.708-.786h5.06V2.5q0-.074.014-.146q.015-.073.043-.141t.069-.13t.094-.113q.052-.053.113-.094t.13-.069t.141-.043q.072-.014.146-.014t.146.014q.073.015.141.043t.13.069t.113.094q.053.052.094.113t.069.13t.043.141t.014.146");
}

</style>
