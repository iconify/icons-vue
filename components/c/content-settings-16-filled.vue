<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="v1unp-bnw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:content-settings-16-filled" /></template>
<style>
.v1unp-bnw {
  fill: currentColor;
  d: path("M2 4.75A2.75 2.75 0 0 1 4.75 2h6.5A2.75 2.75 0 0 1 14 4.75v1.507a5.5 5.5 0 0 0-1.5-.882v-.376h-9v6.252c0 .69.56 1.25 1.25 1.25h.624a5.5 5.5 0 0 0 .883 1.5H4.75A2.75 2.75 0 0 1 2 11.25zm2.999 1.248h2.339c-.404.284-.767.62-1.08 1h-.759v1.207a5.53 5.53 0 0 0-.41 3.295H5a.5.5 0 0 1-.5-.5V6.498a.5.5 0 0 1 .5-.5M6.504 8.72l.358.35a2 2 0 0 1 0 2.861l-.358.35q.196.467.483.874l.395-.119a2 2 0 0 1 2.52 1.454l.116.484a4.3 4.3 0 0 0 .963 0l.115-.484a2 2 0 0 1 2.52-1.454l.396.119q.287-.406.483-.874l-.358-.35a2 2 0 0 1 0-2.861l.358-.35a4.5 4.5 0 0 0-.483-.873l-.396.118a2 2 0 0 1-2.52-1.453l-.115-.484a4.3 4.3 0 0 0-.963 0l-.115.484a2 2 0 0 1-2.52 1.453l-.396-.118q-.288.406-.483.873m3.995 2.78a1 1 0 1 1 0-2a1 1 0 0 1 0 2");
}

</style>
