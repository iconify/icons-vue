<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="y9tr6bcfx"><path class="wwdxrozqk"/><path class="erplxea7u"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:buzzfeed" /></template>
<style>
.erplxea7u {
  d: path("M17.01 14.456c1.425 0 2.58 1.15 2.58 2.57s-1.155 2.569-2.58 2.569h-4.26V9.317h4.259c1.425 0 2.58 1.15 2.58 2.57s-1.155 2.569-2.58 2.569Zm-.001 0h-4.258m8.464-5.139h6.839l-6.839 10.278h6.839m-15.303 7.203h3.355m-3.355 5.139V21.659h5.162m2.185 10.279V21.66h2.323c2.494 0 4.516 2.013 4.516 4.497v1.285c0 2.483-2.022 4.496-4.516 4.496z");
}

.wwdxrozqk {
  d: path("M35.306 5.5H5.5v29.806l7.194 7.194H42.5V12.694z");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
