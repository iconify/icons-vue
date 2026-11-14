<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yl6rcrbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:eye-anatomy" /></template>
<style>
.yl6rcrbeo {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M4.916 16.624q.081-.054.16-.11q.464.693 1.09 1.32Q8.583 20.25 12 20.25t5.834-2.416q1.904-1.905 2.308-4.431q.369.502.646 1.334q.048.142.145.254q.098.113.232.18q.133.067.282.077q.149.011.29-.036q.07-.024.134-.06q.065-.037.12-.085q.056-.049.101-.107q.046-.059.079-.125t.052-.137q.02-.071.025-.145t-.004-.147t-.032-.143q-.681-2.041-1.975-2.755q-.163-3.101-2.403-5.342Q15.417 3.75 12 3.75T6.166 6.166q-.626.627-1.09 1.32q-.079-.056-.16-.11q-.059-.04-.125-.067t-.135-.043q-.07-.014-.141-.016q-.071-.001-.142.011t-.137.037t-.127.062t-.114.085t-.095.105Q2.5 9.417 2.5 12t1.4 4.45q.043.057.095.105t.114.085t.127.062q.067.025.137.037t.142.011t.141-.016t.135-.043q.066-.027.125-.067");
}

</style>
