<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="vwe5v181m"/><circle class="kb0uz2bvp"/><circle class="gpn8l89hg"/><circle class="lvjpbib7u"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:holly-sharp" /></template>
<style>
.gpn8l89hg {
  cx: 9.1px;
  cy: 17.75px;
  r: 1.5px;
}

.kb0uz2bvp {
  cx: 12px;
  cy: 16.94px;
  r: 1.5px;
}

.lvjpbib7u {
  cx: 14.9px;
  cy: 17.75px;
  r: 1.5px;
}

.vwe5v181m {
  d: path("m9.11 12.8l.65-1.44q.21-.45.34-.93l.29-1.07l.13-.48l-.39-.31l-.91-.73l-.39-.31l.1-.49l.25-1.14l.1-.49l-.42-.27l-1.01-.63q-.42-.27-.86-.51L5.7 3.3l-.44-.24l-.19.46l-.56 1.37q-.19.46-.35.93l-.37 1.15l-.16.47l.39.31l.91.72l.39.31l-.1.49l-.25 1.14l-.1.49l.41.29l.89.64q.41.29.86.51l1.42.69l.45.22zm8.72-.97l.89-.64l.41-.29l-.1-.49l-.25-1.14l-.1-.49l.39-.31l.91-.72l.39-.31l-.16-.47l-.37-1.15q-.16-.47-.35-.93l-.56-1.37l-.19-.46l-.44.24l-1.29.7q-.44.24-.86.51l-1.01.63l-.42.27l.1.49l.25 1.14l.1.49l-.39.31l-.91.73l-.39.31l.13.48l.29 1.07q.13.48.34.93l.65 1.44l.21.45l.45-.22l1.42-.69q.45-.22.86-.51Z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
