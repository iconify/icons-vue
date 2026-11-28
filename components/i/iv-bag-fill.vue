<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path clip-rule="evenodd" class="jcknhqbjm"/><path class="oi9b--3gu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:iv-bag-fill" /></template>
<style>
.jcknhqbjm {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M15.437 12L18.874 12C19.4263 12 19.874 12.4477 19.874 13C19.874 13.0841 19.8634 13.1678 19.8424 13.2493C19.2874 15.4056 17.3312 17 15 17L9 17C6.6688 17 4.7126 15.4056 4.1576 13.2493C4.1366 13.1678 4.126 13.0841 4.126 13C4.126 12.4477 4.5737 12 5.126 12L12 12ZM8.5 10L5 10C4.4477 10 4 9.5523 4 9L4 5C4 2.7908 5.7908 1 8 1L12 1L16 1C18.2092 1 20 2.7908 20 5L20 9C20 9.5523 19.5523 10 19 10L12 10ZM13.5 6.5C13.5 5.6716 12.8284 5 12 5C11.1716 5 10.5 5.6716 10.5 6.5C10.5 7.3284 11.1716 8 12 8C12.8284 8 13.5 7.3284 13.5 6.5Z");
  stroke: none;
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.oi9b--3gu {
  d: path("M12 16L12 19C12 20.6569 10.6569 22 9 22L7 22");
}

</style>
