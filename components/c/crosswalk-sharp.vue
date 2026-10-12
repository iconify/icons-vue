<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="jpj6svb4n"/><circle class="u2vhcz6gc"/><path class="brk278bus"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:crosswalk-sharp" /></template>
<style>
.brk278bus {
  d: path("m12.45 6.6l-1.2 3.45l1.8 1.65v2.4m-1.8-4.05l-1.5 4.05m-.6-5.4l1.05-1.8l2.1-.3l1.35 1.8l1.65.6");
}

.jpj6svb4n {
  d: path("M4.5 16.75v4.5m3.75-4.5v4.5m3.75-4.5v4.5m3.75-4.5v4.5m3.75-4.5v4.5");
}

.u2vhcz6gc {
  cx: 12.9px;
  cy: 4.05px;
  r: 1.25px;
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
