<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i2jo_3b2d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:bee-hotel" /></template>
<style>
.i2jo_3b2d {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M4.613 7.91q-.863.748-.863 1.889v9.951q0 1.036.732 1.768t1.768.732h11.5q1.036 0 1.768-.732t.732-1.768V9.799q0-1.141-.863-1.889l-5.75-4.984q-1.637-1.418-3.274 0zM9.5 11.75q0-2.5 2.5-2.5q1.036 0 1.768.732t.732 1.768t-.732 1.768T12 14.25q-2.5 0-2.5-2.5m-.75 2.75q2.5 0 2.5 2.5t-2.5 2.5t-2.5-2.5t2.5-2.5m4 2.5q0-2.5 2.5-2.5t2.5 2.5t-2.5 2.5t-2.5-2.5");
}

</style>
