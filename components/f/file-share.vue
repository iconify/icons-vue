<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="is6rc6bje"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:file-share" /></template>
<style>
.is6rc6bje {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M7 1.75h6.5q-.074 0-.146.014q-.073.015-.141.043t-.13.069t-.113.094q-.053.052-.094.113t-.069.13t-.043.141t-.014.146v4q0 2.75 2.75 2.75h4q.074 0 .146-.014q.073-.015.141-.043t.13-.069q.061-.041.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146V19q0 1.346-.952 2.298T17 22.25H7q-1.346 0-2.298-.952T3.75 19V5q0-1.346.952-2.298T7 1.75m7.25.75q0-.149-.057-.287t-.162-.243l5.999 6q-.105-.106-.243-.163T19.5 7.75h-4q-1.25 0-1.25-1.25zm2.75 9q0-2-2-2t-2 2q0 .082.003.16l-2.679 1.339q-.558-.5-1.324-.5q-.829 0-1.415.586Q7 13.671 7 14.499v.002q0 .828.585 1.414q.586.586 1.415.586q.766 0 1.324-.5l2.679 1.339q-.003.078-.003.16q0 2 2 2t2-2t-2-2q-.94 0-1.439.442l-2.566-1.283q.005-.079.005-.16q0-.08-.005-.158l2.566-1.283q.499.442 1.439.442q2 0 2-2");
}

</style>
