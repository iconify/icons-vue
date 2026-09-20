<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wv0npm03x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:battery-charging-50-2-outline-rounded" /></template>
<style>
.wv0npm03x {
  fill: currentColor;
  d: path("M3 17q-.425 0-.712-.288T2 16V8q0-.425.288-.712T3 7h11.45q.425 0 .713.288T15.45 8t-.287.713T14.45 9H10v6h3.825q.425 0 .713.288t.287.712t-.287.713t-.713.287zm14.375-4H15.05q-.325 0-.462-.275t.062-.525l3.6-4.525q.125-.15.288-.175t.312.025t.25.2t.05.35L18.625 11h2.325q.325 0 .463.275t-.063.525l-3.6 4.525q-.125.15-.288.175t-.312-.025t-.25-.2t-.05-.35z");
}

</style>
