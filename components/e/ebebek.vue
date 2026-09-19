<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="tf_mxco9q"/><path class="yb3ia5bso"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:ebebek" /></template>
<style>
.tf_mxco9q {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M16.813 15.75c-1.772-3.238-.915-7.224 2.048-9.53s7.213-2.292 10.16.032s3.778 6.315 1.984 9.542m.001 0c2.975 1.84 5.271 4.434 6.408 7.752c4.888 14.452-16.489 18.145-18.618 9.297c-.409-2.043.369-3.702 1.535-5.258c-3.001-4.203 2.65-9.267 6.5-5.823a4.39 4.39 0 0 1 .646 5.82");
}

.yb3ia5bso {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M13.088 19.199c-.854 1.172-1.71 2.348-2.398 3.986s-1.21 3.74-1.005 6.458c.205 2.716 1.138 6.048 3.629 8.683c2.49 2.636 6.54 4.575 10.286 5.051c3.747.476 7.191-.511 9.6-1.571c2.41-1.06 3.73-2.146 5.16-3.324");
}

</style>
