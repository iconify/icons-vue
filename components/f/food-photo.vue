<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tdwaaialz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:food-photo" /></template>
<style>
.tdwaaialz {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M3.055 6.555Q2.25 7.361 2.25 8.5V18q0 2.75 2.75 2.75h14q2.75 0 2.75-2.75V8.5q0-2.75-2.75-2.75h-2.075l-1.282-2.136q-.05-.083-.119-.151q-.07-.068-.154-.116q-.085-.048-.179-.072q-.094-.025-.191-.025H9q-.097 0-.191.025q-.094.024-.179.072t-.154.116t-.119.151L7.075 5.75H5q-1.139 0-1.945.805M7.5 13q0-1.864 1.318-3.182T12 8.5t3.182 1.318T16.5 13t-1.318 3.182T12 17.5t-3.182-1.318T7.5 13");
}

</style>
