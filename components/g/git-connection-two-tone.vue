<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="bz2v9tb7f"/><path class="lq-vfcc-t"/><path class="dsqq6boqn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:git-connection-two-tone" /></template>
<style>
.bz2v9tb7f {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M22 18C22 15.7909 20.2091 14 18 14C15.7909 14 14 15.7909 14 18C14 20.2091 15.7909 22 18 22C20.2091 22 22 20.2091 22 18ZM2 5C2 3.34315 3.34315 2 5 2H7C8.65685 2 10 3.34315 10 5V7C10 8.65685 8.65685 10 7 10H5C3.34315 10 2 8.65685 2 7V5Z");
  stroke: none;
}

.dsqq6boqn {
  d: path("M18 15C19.6569 15 21 16.3431 21 18C21 19.6569 19.6569 21 18 21C16.3431 21 15 19.6569 15 18C15 16.3431 16.3431 15 18 15ZM5 3H7C8.10457 3 9 3.89543 9 5V7C9 8.10457 8.10457 9 7 9H5C3.89543 9 3 8.10457 3 7V5C3 3.89543 3.89543 3 5 3Z");
}

.lq-vfcc-t {
  d: path("M6 9V14C6 16.2091 7.79086 18 10 18H11M13 6H14C16.2091 6 18 7.79086 18 10V15");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
