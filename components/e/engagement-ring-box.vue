<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x40_c9xgs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:engagement-ring-box" /></template>
<style>
.x40_c9xgs {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("m3.253 13.429l1-10.5q.007-.069.026-.136t.05-.129t.073-.117t.093-.102q.052-.047.111-.083T4.73 2.3q.064-.025.132-.037q.069-.013.138-.013h14q.069 0 .138.013q.068.012.132.037q.065.025.124.062q.059.036.111.083q.051.047.093.102t.073.117t.05.129t.026.136l1 10.5l.001.02q1.002.837 1.002 2.676v2.25q0 3.375-3.375 3.375H5.625q-1.398 0-2.386-.989q-.989-.988-.989-2.386v-2.25q0-1.398.989-2.386l.038-.039q-.037-.133-.024-.271M18.318 3.75H5.682l-.866 9.091q.386-.091.809-.091h3.459Q8.75 12.042 8.75 11q0-2.345 1.692-2.998q-.595-.622-.262-1.427q.341-.824 1.233-.825h1.173q.893.001 1.234.825q.333.806-.262 1.427Q15.25 8.655 15.25 11q0 1.042-.334 1.75h3.459q.43 0 .805.055z");
}

</style>
