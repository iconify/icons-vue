<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="cpk0fnbgt"/><g class="y9tr6bcfx"><path class="ctxx5nbqk"/><path class="exwbqdbum"/><path class="i234k8njd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:dontkillmyapp" /></template>
<style>
.cpk0fnbgt {
  cx: 24px;
  cy: 24px;
  r: 21.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.ctxx5nbqk {
  d: path("m21.565 23.351l-1.884-10.053c-.35-1.784 2.738-2.618 3.067-.985l2.774 10.872c.147.728 1.627.477 2.015-.95l2.134-10.194c.323-1.704 3.259-.599 3.059.618l-2.666 16.276");
}

.exwbqdbum {
  d: path("M22.815 28.384c-.208-1.357 1.081-2.507 1.794-2.124l5.661 2.776c.713.35.952 1.32 1.137 2.091c.229.953.319 2.043-.078 2.939c-.54 1.219-1.555 2.778-2.888 2.767l-11.379-.088c-.82-.007-1.808-.857-1.801-1.678l.068-8.338c0-1.497 2.788-2.838 3.016-2.002");
}

.i234k8njd {
  d: path("m19.747 31.877l-1.402-7.15c-.16-.795 3.025-2.163 3.22-1.376l1.866 7.517");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
