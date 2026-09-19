<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<g class="tzvfjcbcx"><path class="hgin80vss"/><ellipse class="uksp39rfq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione:dotted-six-pointed-star" /></template>
<style>
.hgin80vss {
  d: path("M50.3 32L60 16H40.5L32 2l-8.5 14H4l9.7 16L4 48h19.5L32 62l8.5-14H60zm.4-11l-3.5 5.9l-3.6-5.9zm-6.6 11l-6.6 11H26.4l-6.6-11l6.6-11h11.1zM32 11.7l2.6 4.3h-5.1zM13.3 21h7.2l-3.6 5.9zm0 22l3.5-5.9l3.6 5.9zM32 52.3L29.4 48h5.1zm15.2-15.2l3.5 5.9h-7.2z");
}

.tzvfjcbcx {
  fill: var(--svg-color--c28fef, #c28fef);
}

.uksp39rfq {
  cx: 32px;
  cy: 32px;
  rx: 4.2px;
  ry: 4.3px;
}

</style>
