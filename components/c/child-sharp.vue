<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><circle class="t02-z8bti"/><path class="ev6b64_pr"/><circle class="z_28vwb8i"/><path class="o3hv5guuh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:child-sharp" /></template>
<style>
.ev6b64_pr {
  d: path("M4.5 21.25h11.75v-.75c0-2.2-2.81-3.75-6.25-3.75S3.75 18.3 3.75 20.5v.75z");
}

.o3hv5guuh {
  d: path("M18.25 8.25c-.75 1.5.75 3 0 4.5");
}

.t02-z8bti {
  cx: 10px;
  cy: 10.5px;
  r: 3.25px;
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.z_28vwb8i {
  cx: 18.25px;
  cy: 5.75px;
  r: 2.5px;
}

</style>
