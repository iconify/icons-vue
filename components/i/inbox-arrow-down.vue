<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tpm_pbczs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:inbox-arrow-down" /></template>
<style>
.tpm_pbczs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M18.8952 7.0905L21.5574 11.4317C21.8468 11.9036 22 12.4464 22 13L22 17C22 18.6569 20.6569 20 19 20L5 20C3.3431 20 2 18.6569 2 17L2 13C2 12.4464 2.1532 11.9036 2.4426 11.4317L5.1048 7.0905M2 13L8 13L10 16L14 16L16 13L22 13M12 4V11M9 8L12 11L15 8");
}

</style>
