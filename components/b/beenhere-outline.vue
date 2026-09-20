<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oc8kl7p6b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:beenhere-outline" /></template>
<style>
.oc8kl7p6b {
  fill: currentColor;
  d: path("m12 23l-7.2-5.4q-.375-.275-.587-.7T4 16V4q0-.825.588-1.412T6 2h12q.825 0 1.413.588T20 4v12q0 .475-.213.9t-.587.7zm0-2.5l6-4.5V4H6v12zM10.95 15l5.65-5.65l-1.4-1.45l-4.25 4.25l-2.1-2.1l-1.45 1.4zM12 4H6h12z");
}

</style>
