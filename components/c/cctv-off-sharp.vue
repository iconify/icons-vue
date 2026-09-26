<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yt6y7e71h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:cctv-off-sharp" /></template>
<style>
.yt6y7e71h {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12.8937 12.8937L4.47 9.4903L5.9147 5.9147M8.7904 3.6861L17.2913 7.1207L15.6178 11.2628M16.5421 8.9751L21.0001 8.6191L18.6905 14.3355M6.788 10.4269L6.788 17L3 17M3 12L3 22M1.7071 1.7071L22.2929 22.2929");
}

</style>
