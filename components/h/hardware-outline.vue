<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f__qcpb-a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:hardware-outline" /></template>
<style>
.f__qcpb-a {
  fill: currentColor;
  d: path("M10 21q-.425 0-.712-.288T9 20V8H4q0-2.075 1.463-3.537T9 3h6v3l3-3h2v8h-2l-3-3v12q0 .425-.288.713T14 21zm1-2h2v-6h-2zm0-8h2V5H9q-.65 0-1.225.263t-1 .737H11zm1 1");
}

</style>
