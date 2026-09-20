<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<defs><radialGradient id="SVGhEfk9dUr" cx="-236.884" cy="-171.086" r=".006" gradientTransform="matrix(2157.515 0 0 -2491.283 511096.688 -426208.482)" gradientUnits="userSpaceOnUse"><stop offset="0" class="sabca2ywv"/><stop offset=".593" class="bow5c8bgj"/><stop offset="1" class="ezk-b-b1n"/></radialGradient></defs><path fill="url(#SVGhEfk9dUr)" class="kjupbp0iz"/><path class="wainf-6wu"/><path class="yo7ze8bfb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:file-type-webpack" /></template>
<style>
.bow5c8bgj {
  stop-color: var(--svg-color--b9d1f8, #b9d1f8);
}

.ezk-b-b1n {
  stop-color: var(--svg-color--9cb6e0, #9cb6e0);
}

.kjupbp0iz {
  d: path("M16 2.043L3.9 9.032v13.979L16 30l12.106-6.989V9.032Z");
}

.sabca2ywv {
  stop-color: var(--svg-color--93b4e7, #93b4e7);
}

.wainf-6wu {
  fill: var(--svg-color--6f95db, #6f95db);
  d: path("M16 9.133L10 12.6v6.932L16 23l6-3.466V12.6Z");
}

.yo7ze8bfb {
  fill: var(--svg-color--fff, #fff);
  fill-opacity: var(--svg-fill-opacity--0-1, 0.1);
  d: path("M16 2L3.869 9.037L16 15.642L28.131 9.08Zm0 14.548L3.869 22.981L16 29.974l12.088-7.037z");
}

</style>
