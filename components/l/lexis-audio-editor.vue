<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="y9tr6bcfx"><circle class="c4p_zddeb"/><circle class="sva-k_pbn"/><path class="zhk9r5bpx"/></g><g class="y9tr6bcfx"><circle class="xwn9mtb7y"/><circle class="sr1lsti6z"/><path class="ej5-qdbyx"/></g><path class="tv9g7ebvy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:lexis-audio-editor" /></template>
<style>
.c4p_zddeb {
  cx: 35.608px;
  cy: 24px;
  r: 7.892px;
}

.ej5-qdbyx {
  d: path("m10.838 22.695l-4.49-3.77m5.693 3.076l-1.016-5.774m1.014 9.771l-1.02 5.774m-.206-6.448l-4.468 3.747m7.955-5.764l5.51-2.004m-5.511 3.392l5.509 2.007");
}

.sr1lsti6z {
  cx: 12.392px;
  cy: 24px;
  r: 2.03px;
}

.sva-k_pbn {
  cx: 35.608px;
  cy: 24px;
  r: 2.03px;
}

.tv9g7ebvy {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M12.392 31.892h23.216");
}

.xwn9mtb7y {
  cx: 12.392px;
  cy: 24px;
  r: 7.892px;
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.zhk9r5bpx {
  d: path("m34.913 22.093l-2.005-5.509m3.394 5.509l2.005-5.509m-4.004 8.97l-3.768 4.492m3.043-5.688l-5.743 1.012m9.771-1.018l5.774 1.018m-6.468.185l3.769 4.491");
}

</style>
