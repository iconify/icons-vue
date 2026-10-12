<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="apida2bpz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:bone-saw" /></template>
<style>
.apida2bpz {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10.25 6H19a2.25 2.25 0 0 1 2.25 2.25v1A2.25 2.25 0 0 1 19 11.5h-1.75v8a1.75 1.75 0 0 1-1.75 1.75h-1a1.75 1.75 0 0 1-1.75-1.75v-8h-2.5Zm4.25 2.75h4.25m-10.23.19l-3.37 2.83q-.23.19-.22-.11v-.41q.01-.3-.25-.44l-.37-.2q-.26-.15-.15-.43l.15-.39q.11-.28-.09-.5l-.27-.31q-.2-.23 0-.46l.27-.31q.2-.22.09-.5l-.15-.39q-.11-.28.15-.43l.37-.2q.26-.14.25-.44v-.41q-.01-.3.22-.11l3.37 2.83q.23.19 0 .38");
}

</style>
