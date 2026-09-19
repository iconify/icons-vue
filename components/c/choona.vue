<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="zz4ndcc-c"/><path class="ual4z6m_y"/><ellipse transform="rotate(-32.29 28.772 36.217)" class="aublcdc6f"/><ellipse transform="rotate(-40.45 15.086 32.615)" class="rs-260s7c"/><path class="ixmyle-kj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:choona" /></template>
<style>
.aublcdc6f {
  cx: 28.772px;
  cy: 36.217px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 2.947px;
  ry: 2.521px;
}

.ixmyle-kj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M14.632 41.998c2.418-.935 3.63-2.736 4.088-4.308m-2.109-11.492c3.68.654 6.988 3.765 7.806 6.81M20.7 22.611c3.681.655 6.988 3.766 7.807 6.81");
}

.rs-260s7c {
  cx: 15.086px;
  cy: 32.615px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 1.321px;
  ry: 1.768px;
}

.ual4z6m_y {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M11.195 24.874c-.69-.91-1.355-2.417-.14-3.982c1.774-2.277 3.328-1.647 4.145.385");
}

.zz4ndcc-c {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M30.592 33.972c1.402-2.3 2.242-4.788 2.242-7.054v-9.039l3.375 3.375l3.83-3.83L27.662 5.5v12.904c-4.344-1.12-10.814.853-15.03 4.917c-4.683 4.496-6.692 11.421-1.997 16.104c5.092 5.092 11.62 3.224 16.28-.992");
}

</style>
