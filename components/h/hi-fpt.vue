<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="y9tr6bcfx"><path class="eypgqjb2m"/><circle class="by5k-tbqg"/><path class="yt2_wubyo"/></g><path class="ge-i_417d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:hi-fpt" /></template>
<style>
.by5k-tbqg {
  cx: 31.378px;
  cy: 8.189px;
  r: 3.689px;
}

.eypgqjb2m {
  d: path("m14.267 43.5l1.415-5.27h2.635m-3.343 2.635h1.713M30.573 43.5l1.415-5.27m-1.746 0h3.491M21.12 43.5l1.415-5.27h1.725c.976 0 1.554.792 1.291 1.77c-.262.977-1.266 1.77-2.241 1.77h-1.726");
}

.ge-i_417d {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M12.933 31.378V8.19m7.377 18.972v4.216m7.38-4.216v4.216M20.31 8.19v4.215M35.068 24v7.379m-7.906-15.284H24");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.yt2_wubyo {
  d: path("M27.162 16.095A7.905 7.905 0 0 1 35.068 24M24 16.095a3.69 3.69 0 0 1-3.69-3.69M12.933 8.19a3.69 3.69 0 1 1 7.378 0m-.001 23.188a3.69 3.69 0 0 1-7.378 0m22.136 0a3.689 3.689 0 1 1-7.379 0m-7.379-4.216a3.69 3.69 0 1 1 7.38 0");
}

</style>
