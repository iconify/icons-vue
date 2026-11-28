<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="bx4fqnbwk"/><path clip-rule="evenodd" class="g71w59b9a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:copy-arrow-right-fill" /></template>
<style>
.bx4fqnbwk {
  d: path("M15.8284 4C15.4046 2.8015 14.2714 2 13 2H5C3.34315 2 2 3.34315 2 5V13C2 14.2714 2.8015 15.4046 4 15.8284");
}

.g71w59b9a {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M11 7L19 7C21.2091 7 23 8.7909 23 11L23 19C23 21.2091 21.2091 23 19 23L11 23C8.7909 23 7 21.2091 7 19L7 11C7 8.7909 8.7909 7 11 7ZM15.5828 16.001L14.2919 17.2919C13.9009 17.683 13.9009 18.317 14.2919 18.7081C14.683 19.0991 15.317 19.0991 15.7081 18.7081L18.7081 15.7081C19.0991 15.317 19.0991 14.683 18.7081 14.2919L17.2081 12.7919L15.7081 11.2919C15.317 10.9009 14.683 10.9009 14.2919 11.2919C13.9009 11.683 13.9009 12.317 14.2919 12.7081L15.5839 13.999L15 13.999L12 13.999C11.4471 13.999 10.999 14.4471 10.999 15C10.999 15.5529 11.4471 16.001 12 16.001Z");
  stroke: none;
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
