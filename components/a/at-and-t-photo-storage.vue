<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="vr9dheffy"/><path class="pvz6eryxe"/><path class="f9yyphbzi"/><path class="gnkaeb6id"/><circle class="kcgtirbzc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:at-and-t-photo-storage" /></template>
<style>
.f9yyphbzi {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m34.31 17.493l-5.504-1.779l-.488 5.635Z");
}

.gnkaeb6id {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M27.84 29.404c4.198-.896 7.657-4.225 3.474-10.005m3.892 17.42l-5.423-5.423l-3.919 3.919l-1.326-1.327l-7.925 7.925");
}

.kcgtirbzc {
  cx: 18.525px;
  cy: 30.759px;
  r: 1.812px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.pvz6eryxe {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M35.206 30.976c11.062-.684 9.456-13.009 4.421-14.004c-1.627-4.886-5.002-5.324-8.307-5.942c-3.537-6.38-10.197-6.096-14.43-1.926a5.99 5.99 0 0 0-6.039 3.561c-11.563 5.325-4.96 16.486 1.133 16.727");
}

.vr9dheffy {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M35.206 25.094v16.819H11.984V25.094Z");
}

</style>
