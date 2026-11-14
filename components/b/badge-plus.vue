<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jk4bodb7j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:badge-plus" /></template>
<style>
.jk4bodb7j {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m20.125 13.375l-.606.606a2.63 2.63 0 0 0-.769 1.856v.913a2 2 0 0 1-2 2h-.913a2.63 2.63 0 0 0-1.856.769l-.606.606a1.945 1.945 0 0 1-2.75 0l-.606-.606a2.63 2.63 0 0 0-1.856-.769H7.25a2 2 0 0 1-2-2v-.913a2.63 2.63 0 0 0-.769-1.856l-.606-.606a1.945 1.945 0 0 1 0-2.75l.606-.606a2.63 2.63 0 0 0 .769-1.856V7.25a2 2 0 0 1 2-2h.913a2.63 2.63 0 0 0 1.856-.769l.606-.606a1.945 1.945 0 0 1 2.75 0l.606.606a2.63 2.63 0 0 0 1.856.769h.913a2 2 0 0 1 2 2v.913a2.63 2.63 0 0 0 .769 1.856l.606.606a1.945 1.945 0 0 1 0 2.75M12 8.5v7M8.5 12h7");
}

</style>
