<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f0r7vto7a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:channel-mix" /></template>
<style>
.f0r7vto7a {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M5.5 8.25q0-2.692 1.904-4.596T12 1.75t4.596 1.904T18.5 8.25q0 .106-.003.211q.859.453 1.599 1.193Q22 11.558 22 14.25t-1.904 4.596T15.5 20.75q-1.959 0-3.5-1.008q-1.541 1.008-3.5 1.008q-2.692 0-4.596-1.904T2 14.25t1.904-4.596q.74-.74 1.599-1.193Q5.5 8.356 5.5 8.25");
}

</style>
