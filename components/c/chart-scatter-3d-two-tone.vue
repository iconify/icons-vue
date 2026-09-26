<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="v1hv90bjp"/><path class="d537sub7e"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:chart-scatter-3d-two-tone" /></template>
<style>
.d537sub7e {
  fill: currentColor;
  d: path("M14.5 5C14.5 5.8284 13.8284 6.5 13 6.5C12.1716 6.5 11.5 5.8284 11.5 5C11.5 4.1716 12.1716 3.5 13 3.5C13.8284 3.5 14.5 4.1716 14.5 5ZM20.5 8C20.5 8.8284 19.8284 9.5 19 9.5C18.1716 9.5 17.5 8.8284 17.5 8C17.5 7.1716 18.1716 6.5 19 6.5C19.8284 6.5 20.5 7.1716 20.5 8ZM15.5 11C15.5 11.8284 14.8284 12.5 14 12.5C13.1716 12.5 12.5 11.8284 12.5 11C12.5 10.1716 13.1716 9.5 14 9.5C14.8284 9.5 15.5 10.1716 15.5 11Z");
  stroke: none;
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.v1hv90bjp {
  stroke-opacity: 0.4;
  d: path("M8 3L8 16L21 16M8 16L3 21");
}

</style>
