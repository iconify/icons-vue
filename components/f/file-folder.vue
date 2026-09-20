<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="xromw8b4l"/><path class="rfj7jsbib"/><path class="f_jmrpb6b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noto:file-folder" /></template>
<style>
.f_jmrpb6b {
  fill: none;
  stroke: var(--svg-color--fff9c4, #fff9c4);
  stroke-linecap: round;
  stroke-miterlimit: 10;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("m21.63 58.73l22.76-3.89c5.7-1.27 6.61-3.43 6.6-7.97L51 45.7c.18-3.42 1.84-5.44 5.21-6.02l55.67-9.65");
}

.rfj7jsbib {
  fill: var(--svg-color--ffe36c, #ffe36c);
  d: path("M112.56 91.65L114.58 32c0-1.79-1.56-3.15-3.27-2.85l-56.27 9.62a5.724 5.724 0 0 0-4.75 5.29l-.23 3.77a6.5 6.5 0 0 1-5.41 6.02L22 57.66a4.67 4.67 0 0 0-3.89 4.6l-2.59 54.38s.33.14 4.04-.8l89.2-21.11c1.35-.22 2.89-1.48 3.8-3.08");
}

.xromw8b4l {
  fill: var(--svg-color--f3ab47, #f3ab47);
  d: path("M46.19 27.93v-1.74c0-3.47-2.08-4.19-4.36-3.78l-19.1 3.45c-2.29.41-3.97 2.47-3.97 4.87v4.44c0 1.62-1.13 3.01-2.68 3.29l-.34.06c-1.34.24-2.33 1.44-2.33 2.85l1.08 74.03s-.08 1.18 1.03 1.26c1.15.08 2.02-.8 3.17-1.07l89.64-21.36c1.34-.24 2.33-1.44 2.33-2.85V25.35c0-1.79-1.56-3.15-3.27-2.85l-56.31 9.69c-2.55.45-4.89-.51-4.89-4.26");
}

</style>
