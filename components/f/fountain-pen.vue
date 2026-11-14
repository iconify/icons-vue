<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pwote_btf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:fountain-pen" /></template>
<style>
.pwote_btf {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M14.5 2.75h-5q-.074 0-.146.014q-.073.015-.141.043t-.13.069t-.113.094q-.053.052-.094.113t-.069.13t-.043.141t-.014.146t.014.146q.015.073.043.141t.069.13t.094.113q.052.053.113.094t.13.069t.141.043t.146.014h5q.074 0 .146-.014q.073-.015.141-.043t.13-.069t.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146t-.014-.146q-.015-.073-.043-.141t-.069-.13t-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043q-.072-.014-.146-.014M8.053 13.315l1.908 4.089h.001q.433.928 1.288 1.192V14q0-.043.005-.086Q10 13.584 10 12q0-2 2-2t2 2q0 1.584-1.255 1.914q.005.043.005.086v4.596q.855-.264 1.289-1.192l1.908-4.089q.349-.747.132-1.543l-1.054-3.865q-.453-1.657-2.171-1.657h-1.708q-1.718 0-2.171 1.658l-1.054 3.864q-.217.796.132 1.543");
}

</style>
