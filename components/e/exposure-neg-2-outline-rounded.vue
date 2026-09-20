<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z-r4njbje"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:exposure-neg-2-outline-rounded" /></template>
<style>
.z-r4njbje {
  fill: currentColor;
  d: path("M20.058 17.962H13.44q-.166 0-.282-.117q-.117-.116-.117-.281v-.575q0-.037.104-.275l4.281-4.375q.864-.914 1.259-1.52q.395-.607.395-1.357q0-1.033-.707-1.717q-.707-.683-1.928-.683q-.765 0-1.343.3q-.578.302-.96.842q-.135.177-.33.235t-.378-.016q-.194-.079-.276-.274t.022-.372q.506-.76 1.3-1.249q.796-.49 1.977-.49q1.69 0 2.68 1.005t.989 2.419q0 .952-.477 1.742t-1.442 1.78L14.404 16.9l.012.062h5.642q.213 0 .356.143t.144.356t-.144.357t-.356.144M8.942 13.385h-5q-.213 0-.357-.144t-.143-.356t.143-.357q.144-.144.357-.144h5q.214 0 .357.144q.143.143.143.357q0 .213-.143.356t-.357.144");
}

</style>
