<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="neicvubrs"/><path class="dxj4ljbhs"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:circle-dashed-quarter-duotone" /></template>
<style>
.dxj4ljbhs {
  fill: currentColor;
  d: path("M12 5C15.866 5 19 8.134 19 12C19 12.5523 18.5523 13 18 13L12 13C11.4477 13 11 12.5523 11 12L11 6C11 5.4477 11.4477 5 12 5Z");
  stroke: none;
}

.neicvubrs {
  stroke-opacity: 0.4;
  d: path("M21.8769 10.4357C22.041 11.4721 22.041 12.5279 21.8769 13.5643M20.0902 17.8778C19.4734 18.7268 18.7268 19.4734 17.8778 20.0902M13.5643 21.8769C12.5279 22.041 11.4721 22.041 10.4357 21.8769M6.1222 20.0902C5.2732 19.4734 4.5266 18.7268 3.9098 17.8778M2.1231 13.5643C1.959 12.5279 1.959 11.4721 2.1231 10.4357M3.9098 6.1222C4.5266 5.2732 5.2732 4.5266 6.1222 3.9098M10.4357 2.1231C11.4721 1.959 12.5279 1.959 13.5643 2.1231M17.8778 3.9098C18.7268 4.5266 19.4734 5.2732 20.0902 6.1222");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
