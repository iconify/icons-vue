<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="bx4fqnbwk"/><path class="o7rgvpb-h"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:copy-fill" /></template>
<style>
.bx4fqnbwk {
  d: path("M15.8284 4C15.4046 2.8015 14.2714 2 13 2H5C3.34315 2 2 3.34315 2 5V13C2 14.2714 2.8015 15.4046 4 15.8284");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.o7rgvpb-h {
  fill: currentColor;
  d: path("M11 7H19C21.20912 7 23 8.79088 23 11V19C23 21.20912 21.20912 23 19 23H11C8.79088 23 7 21.20912 7 19V11C7 8.79088 8.79088 7 11 7Z");
  stroke: none;
}

</style>
