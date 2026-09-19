<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w-dodqc6i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:baseline-assistant-direction" /></template>
<style>
.w-dodqc6i {
  fill: currentColor;
  d: path("M14 10H9c-.6 0-1 .4-1 1v4h2v-3h4v2.5l3.5-3.5L14 7.5zm-2-9C5.9 1 1 5.9 1 12s4.9 11 11 11s11-4.9 11-11S18.1 1 12 1m7.73 11.58l-7.19 7.22c-.35.27-.79.27-1.15 0L4.2 12.58a.93.93 0 0 1 0-1.16l7.19-7.22c.35-.27.79-.27 1.15 0l7.19 7.22c.36.27.36.8 0 1.16");
}

</style>
