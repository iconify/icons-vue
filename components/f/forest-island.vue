<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="y9tr6bcfx"><path class="uj6hk8brv"/><path class="gx9z22b3g"/><ellipse class="y1vjonbcc"/><ellipse transform="rotate(-81.41 14.022 12.508)" class="y4ztp59sg"/><ellipse transform="rotate(-84.293 19.14 16.223)" class="fby94rb_d"/><path class="xt2cfw0bi"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:forest-island" /></template>
<style>
.fby94rb_d {
  cx: 19.139px;
  cy: 16.223px;
  rx: 2.047px;
  ry: 4.795px;
}

.gx9z22b3g {
  d: path("M12.417 15.774s-.133.568.629 1.692m6.218 20.2l-.125.944l-6.855 2.724l2.147 1.464l4.708.204l2.182-3.37l-.16-1.801m6.621.017l.048 1.681l-4.813 3.78l3.047 1.191l4.605-.545l-1.04-4.63l-.138-1.84");
}

.uj6hk8brv {
  d: path("M34.254 25.164c1.437 2.82 1.9 7.05 4.994 7.608c1.06.19 1.825-.672 2.106-1.686c.3-1.09-.196-3.368-.523-6.133c-.39-3.3-.699-6.67-1.338-6.29l-1.86 1.108a19.9 19.9 0 0 0-3.82-4.96c1.114-5.763-3.3-11.547-10.567-11.304c-9.727.327-10.671 6.523-10.83 12.267c-1.51 1.607-2.738 2.306-3.971 3.755c-.644.757-2.145 2.312-1.855 3.035l1.567 3.9c1.74 11.484 7.966 10.83 13.476 11.414c9.814 1.04 12.783-2.621 15.27-6.694");
}

.xt2cfw0bi {
  d: path("M8.157 26.464s-.166-2.188.665-4.265");
}

.y1vjonbcc {
  cx: 27.812px;
  cy: 14.504px;
  rx: 2.11px;
  ry: 2.228px;
}

.y4ztp59sg {
  cx: 14.022px;
  cy: 12.508px;
  rx: 2.291px;
  ry: 1.174px;
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
