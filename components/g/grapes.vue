<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ya0x-_jsp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:grapes" /></template>
<style>
.ya0x-_jsp {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M12.75 6.5V3q0-.074-.014-.146q-.015-.073-.043-.141t-.069-.13t-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043Q12.074 2.25 12 2.25t-.146.014q-.073.015-.141.043t-.13.069t-.113.094q-.053.052-.094.113t-.069.13t-.043.141T11.25 3v3.5q0 .07.013.139q-.937-.889-2.763-.889q-3.75 0-3.75 3.75q0 3.688 3.627 3.749q-.127.562-.127 1.251q0 2.516 1.689 3.344q-.439.609-.439 1.656Q9.5 22 12 22q1.036 0 1.768-.732T14.5 19.5q0-.916-.572-1.594q1.822-.792 1.822-3.406q0-.689-.127-1.251q3.627-.061 3.627-3.749q0-3.75-3.75-3.75q-1.826 0-2.763.889q.013-.069.013-.139m-.458.691q-.174.283-.292.623q-.118-.34-.292-.623q.14.059.292.059t.292-.059");
}

</style>
