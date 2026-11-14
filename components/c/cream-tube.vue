<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b5hz7feou"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:cream-tube" /></template>
<style>
.b5hz7feou {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("m18.364 5.49l-.354-.354q-1.591-1.591-3.181 0l-.354.354q-.337.336-.531.672q-1.169-.676-2.493.207l-5.515 3.676q-.77.513-1.009 1.344q-.327-.121-.705-.121q-.829 0-1.414.586q-.586.585-.586 1.414t.586 1.414l6.01 6.01q.585.586 1.414.586t1.414-.586t.586-1.414q0-.378-.121-.705q.831-.239 1.344-1.009l3.676-5.515q.883-1.324.207-2.493q.336-.194.672-.531l.354-.354q1.591-1.59 0-3.181M14.75 20q0-4.25 3.75-4.25T22.25 20q0 .074-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014h-6q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069t-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141T14.75 20");
}

</style>
