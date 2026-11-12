<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="vznejxznx"/><path class="owkak0bth"/><path class="nfclxdb-l"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:chat-round-off-linear" /></template>
<style>
.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.nfclxdb-l {
  d: path("M2 2L4.92893 4.92893L5.77811 5.77811L9.63753 9.63753L19.0711 19.0711L22 22");
}

.owkak0bth {
  d: path("M6.862 3.41914C8.36362 2.51807 10.1213 2 12 2C17.5228 2 22 6.47715 22 12C22 13.8787 21.4819 15.6364 20.5809 17.138");
}

.vznejxznx {
  d: path("M4.92915 4.92892C3.1195 6.73857 2.00021 9.23857 2.00021 12C2.00021 13.5997 2.37583 15.1116 3.04367 16.4525C3.22115 16.8088 3.28022 17.2161 3.17733 17.6006L2.58172 19.8266C2.32317 20.793 3.20723 21.677 4.17356 21.4185L6.3996 20.8229C6.78415 20.72 7.19142 20.7791 7.54774 20.9565C8.88858 21.6244 10.4005 22 12.0002 22C14.7616 22 17.2616 20.8807 19.0713 19.0711");
}

</style>
