<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="obxr-wb_r"/><circle class="whyy68m-y"/><path class="h05bcep8g"/><path class="i9pbm4bie"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:customs-officer-sharp" /></template>
<style>
.h05bcep8g {
  d: path("M4.5 21.25a7.5 5.95 0 0 1 15 0");
}

.i9pbm4bie {
  d: path("m12.12 17.42l.2.45l.12.27l.3.03l.48.05l.3.04l-.22.2l-.36.32l-.23.2l.07.3l.1.47l.06.29l-.26-.15l-.42-.24l-.26-.15l-.26.15l-.42.24l-.26.15l.06-.29l.1-.47l.07-.3l-.23-.2l-.36-.32l-.22-.2l.3-.04l.48-.05l.3-.03l.12-.27l.2-.45l.12-.27z");
}

.obxr-wb_r {
  d: path("M7.5 6.5h9m-7.25 0l.4-2.5V2.77l1.23-.02h2.24l1.23.02V4l.4 2.5");
}

.whyy68m-y {
  cx: 12px;
  cy: 10.9px;
  r: 2px;
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
