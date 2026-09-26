<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="e5hhu5pkp"/><path class="ouw8s78nl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:hard-drive" /></template>
<style>
.e5hhu5pkp {
  d: path("M5 11L19 11C20.6569 11 22 12.3431 22 14L22 17C22 18.6569 20.6569 20 19 20L5 20C3.3431 20 2 18.6569 2 17L2 14C2 12.3431 3.3431 11 5 11ZM2.4954 12.3486L4.1448 6.8506C4.6524 5.1587 6.2097 4 7.9761 4L16.0239 4C17.7903 4 19.3476 5.1587 19.8552 6.8506L21.5046 12.3486");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.ouw8s78nl {
  fill: currentColor;
  d: path("M19 15.5C19 16.3284 18.3284 17 17.5 17C16.6716 17 16 16.3284 16 15.5C16 14.6716 16.6716 14 17.5 14C18.3284 14 19 14.6716 19 15.5Z");
  stroke: none;
}

</style>
