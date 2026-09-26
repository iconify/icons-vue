<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="hc5d41b9j"/><path class="rh30l-52v"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:circle-progress-pause-two-tone" /></template>
<style>
.hc5d41b9j {
  stroke-opacity: 0.4;
  d: path("M17.8778 3.90983C18.7268 4.52663 19.4734 5.2732 20.0902 6.12215M21.8769 10.4357C22.041 11.4721 22.041 12.5279 21.8769 13.5643M20.0902 17.8778C19.4734 18.7268 18.7268 19.4734 17.8778 20.0902");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.rh30l-52v {
  d: path("M12 22C6.47715 22 2 17.5229 2 12C2 6.47715 6.47715 2 12 2M9 8V16M15 8V16");
}

</style>
