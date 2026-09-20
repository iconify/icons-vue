<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<defs><path id="SVGf5WaKeet" class="jgt0jacgg"/></defs><circle class="xj1ct6b0b"/><circle class="pwavp4bjb"/><use href="#SVGf5WaKeet" class="z4n2hhy8u"/><path class="aatjulb4f"/><use href="#SVGf5WaKeet" class="pfsdhbbki"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noto:aries" /></template>
<style>
.aatjulb4f {
  fill: var(--svg-color--fafafa, #fafafa);
  d: path("M104.9 45.5c-1.9-5-5.9-8.9-10.9-10.7c-2.4-.9-4.9-1.3-7.3-1.3c-10.3 0-18.9 8.1-19.6 18.4v.2c0 .5-.1.9-.1 1.4l-2.5 20.7c-.1.6-.9.6-1 0L60.9 53v-.8c-.4-10.5-9-18.8-19.6-18.8c-2.7 0-5.4.5-8 1.6c-4.4 1.8-7.9 5.3-9.8 9.6c-1.4 3.3-2 6.8-1.7 10.2c.1 1.5 1.5 2.7 3 2.7h1.5c.6 0 1.1-.1 1.6-.3c1.8-.8 2.8-2.4 2.8-4.1c0-2.4.8-4.7 2.4-7c1.3-1.8 3.2-3 5.4-3.4c1-.2 2-.3 2.9-.3c5.2 0 8.7 3.1 10.2 8.9c.2.9.4 1.8.5 3.1l7.4 44.1c.2 2 1.6 3.6 3.5 4c.3.1.6.1 1 .1c2.3 0 4.2-1.7 4.5-4L76 53.2c1-6.8 4.9-10.8 10.7-10.8c.7 0 1.4 0 2.1.2c2.8.4 5.2 2 6.7 4.3c1.5 2.4 2.1 5 1.8 7.5c-.1.8.1 1.6.7 2.2s1.3.9 2.2.9h1.7c2.5 0 4.6-2 4.6-4.5c-.2-2.4-.6-5-1.6-7.5");
}

.jgt0jacgg {
  fill: var(--svg-color--e68c87, #e68c87);
  d: path("M24 29.7c4.5-7.1 14.1-13 24.1-14.8c2.5-.4 5-.6 7.1.2c1.6.6 2.9 2.1 2 3.8c-.7 1.4-2.6 2-4.1 2.5c-9.3 3-17.9 6.4-23.1 14.3c-2 3-4.9 14.4-8.6 12.3c-3.9-2.3-3.1-9.5 2.6-18.3");
}

.pfsdhbbki {
  opacity: var(--svg-opacity--0-3, 0.3);
}

.pwavp4bjb {
  cx: 60.1px;
  cy: 63.1px;
  r: 56.1px;
  fill: var(--svg-color--ef5350, #ef5350);
}

.xj1ct6b0b {
  cx: 64px;
  cy: 64px;
  r: 60px;
  fill: var(--svg-color--c62828, #c62828);
}

.z4n2hhy8u {
  opacity: var(--svg-opacity--0-6, 0.6);
}

</style>
