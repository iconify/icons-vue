<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="y9tr6bcfx"><path class="vlhuscb2b"/><circle class="mofv9u8xr"/><path class="pjvsf99zc"/></g><path class="uph4zqc9i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:calendar-google-29" /></template>
<style>
.mofv9u8xr {
  cx: 27.609px;
  cy: 22.5px;
  r: 3px;
}

.pjvsf99zc {
  d: path("M24.942 27.389c.445.667 1.223 1.111 2.445 1.111h.222c1.667 0 3-1.333 3-3v-3");
}

.uph4zqc9i {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.5 5.5h-29a4 4 0 0 0-4 4v29a4 4 0 0 0 4 4h24l9-9v-24a4 4 0 0 0-4-4m-5 0v37m-19-28v28m28-9h-37m37-19h-28");
}

.vlhuscb2b {
  d: path("M17.391 22.5c0-1.667 1.333-3 2.889-3s3 1.333 3 3c0 .778-.333 1.556-.889 2.111c-1.222 1-5 3.889-5 3.889h5.889");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
