<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zs09bhbgf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:flip-horizontal" /></template>
<style>
.zs09bhbgf {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M12.75 21V3q0-.074-.014-.146q-.015-.073-.043-.141t-.069-.13t-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043Q12.074 2.25 12 2.25t-.146.014q-.073.015-.141.043t-.13.069t-.113.094q-.053.052-.094.113t-.069.13t-.043.141T11.25 3v18q0 .074.014.146q.015.073.043.141t.069.13q.041.061.094.113q.052.053.113.094t.13.069t.141.043t.146.014t.146-.014q.073-.015.141-.043t.13-.069t.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146m3.211-11.126q-1.709.375-1.711 2.125v4.751q0 1.036.732 1.768t1.768.732h1.515q1.368 0 2.106-1.152q.737-1.153.164-2.395l-2.13-4.615q-.735-1.589-2.444-1.214M9.75 11.999v4.751q0 1.036-.732 1.768t-1.768.732H5.735q-1.368 0-2.106-1.152q-.737-1.153-.164-2.395l2.13-4.615q.735-1.589 2.444-1.214t1.711 2.125");
}

</style>
