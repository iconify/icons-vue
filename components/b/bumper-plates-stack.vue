<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a2sj26bqi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:bumper-plates-stack" /></template>
<style>
.a2sj26bqi {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M12.75 6.25V2.5q0-.074-.014-.146q-.015-.073-.043-.141t-.069-.13t-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043Q12.074 1.75 12 1.75t-.146.014q-.073.015-.141.043t-.13.069t-.113.094q-.053.052-.094.113t-.069.13t-.043.141t-.014.146v3.75h-6q-1.243 0-2.121.879q-.879.878-.879 2.121t.879 2.121q.067.067.136.129q-.069.062-.136.129q-.879.878-.879 2.121t.879 2.121l.005.006q-.884.744-.884 2.373q0 1.243.879 2.121q.878.879 2.121.879h13.5q1.243 0 2.121-.879q.879-.878.879-2.121q0-1.5-.75-2.25q.75-.75.75-2.25T21 11.5q.75-.75.75-2.25q0-3-3-3z");
}

</style>
