<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="exztuguza"/><path class="ts2_6cbic"/><path class="obz7h93vh"/><path class="n0q0gac6b"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:health-id-qr" /></template>
<style>
.exztuguza {
  d: path("M5.188 3h2.125A2.19 2.19 0 0 1 9.5 5.188v2.125A2.19 2.19 0 0 1 7.313 9.5H5.188A2.19 2.19 0 0 1 3 7.313V5.188A2.19 2.19 0 0 1 5.188 3m11.5 0h2.125A2.19 2.19 0 0 1 21 5.188v2.125A2.19 2.19 0 0 1 18.813 9.5h-2.125A2.19 2.19 0 0 1 14.5 7.313V5.188A2.19 2.19 0 0 1 16.688 3m-11.5 11.5h2.125A2.19 2.19 0 0 1 9.5 16.688v2.125A2.19 2.19 0 0 1 7.313 21H5.188A2.19 2.19 0 0 1 3 18.813v-2.125A2.19 2.19 0 0 1 5.188 14.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.n0q0gac6b {
  fill: currentColor;
  d: path("M16.5 14.25h3v2.25h2.25v3H19.5v2.25h-3V19.5h-2.25v-3h2.25Z");
}

.obz7h93vh {
  d: path("M12 4h.01M12 8.5h.01M4 12h.01m4.49 0h.01M12 12h.01");
}

.ts2_6cbic {
  fill: currentColor;
  d: path("M6.25 5.25za1 1 0 0 1 1 1a1 1 0 0 1-1 1a1 1 0 0 1-1-1a1 1 0 0 1 1-1m11.5 0za1 1 0 0 1 1 1a1 1 0 0 1-1 1a1 1 0 0 1-1-1a1 1 0 0 1 1-1m-11.5 11.5za1 1 0 0 1 1 1a1 1 0 0 1-1 1a1 1 0 0 1-1-1a1 1 0 0 1 1-1");
}

</style>
