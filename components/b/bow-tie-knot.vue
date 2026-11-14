<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="obmj9nr9m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:bow-tie-knot" /></template>
<style>
.obmj9nr9m {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M12.079 2.25h-.158q-1.098 0-1.773.866q-.676.865-.41 1.93l.291 1.166q.088.352.239.623l-.006.031l-2 11q-.015.082-.011.166q.003.083.025.164t.061.155t.094.137l3 3.5q.048.056.106.102t.124.079t.137.053t.144.026q.074.005.147-.003q.074-.009.144-.032t.135-.059t.12-.085q.044-.037.081-.081l3-3.5q.055-.063.094-.137t.061-.155t.025-.164t-.011-.166l-2-11l-.006-.031q.151-.271.239-.623l.291-1.166q.266-1.065-.41-1.93q-.675-.866-1.773-.866M9.802 17.783L11.63 7.727q.176.023.37.023t.37-.023l1.828 10.056L12 20.348z");
}

</style>
