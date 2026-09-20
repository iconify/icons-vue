<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h65a30bxr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:devices-fold-outline-sharp" /></template>
<style>
.h65a30bxr {
  fill: currentColor;
  d: path("M10 21V2.975l7-3.05V3h5v18zm2-3.025l3-1.3V3l-3 1.3zM14.675 19H20V5h-3v13.025zM12 17.975V4.3zM2 5V3h2v2zm0 16v-2h2v2zm0-4v-2h2v2zm0-4v-2h2v2zm0-4V7h2v2zm4-4V3h2v2zm0 16v-2h2v2z");
}

</style>
