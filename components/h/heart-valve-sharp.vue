<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="uop060cih"/><path class="a4jlifkmu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:heart-valve-sharp" /></template>
<style>
.a4jlifkmu {
  d: path("m11.18 10.02l-1.37-.64l-.82-.39l.81-.4l1.39-.69l.81-.4l.81.4l1.39.69l.81.4l-.82.39l-1.37.64l-.82.38zm2.94 2.26l1.25-.86l.74-.52l-.06.9l-.1 1.55l-.05.9l-.75.5l-1.3.86l-.75.5l.08-.9l.13-1.51l.08-.9zm-3.43 1.42l.13 1.51l.08.9l-.75-.5l-1.3-.86l-.75-.5l-.05-.9l-.1-1.55l-.06-.9l.74.52l1.25.86l.73.52z");
}

.uop060cih {
  d: path("M12 2.75a9.25 9.25 0 1 1 0 18.5a9.25 9.25 0 1 1 0-18.5Zm0 2.5a6.75 6.75 0 1 0 0 13.5a6.75 6.75 0 1 0 0-13.5Z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
