<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="y9tr6bcfx"><path class="vo29kdbbn"/><path class="k7ww2jbyq"/><circle class="dq0er3phm"/><circle class="uwt0xpiol"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:geometry-dash-meltdown" /></template>
<style>
.dq0er3phm {
  cx: 13.384px;
  cy: 24.215px;
  r: 3.713px;
}

.k7ww2jbyq {
  d: path("m21.91 24.77l2.9-2.9l8.752 8.756l-2.9 2.898zm-5.563 7.087l2.579-2.563l7.2 7.24l-2.578 2.564zm12.998-13.075l2.578-2.564l7.201 7.241l-2.578 2.564z");
}

.uwt0xpiol {
  cx: 24.293px;
  cy: 13.384px;
  r: 3.713px;
}

.vo29kdbbn {
  d: path("m37.171 21.02l2.175-2.174L44.5 24L24 44.5l-5.154-5.155l2.34-2.34m2.804-2.804l3.636-3.636m3.017-3.017l3.484-3.484M18.49 34.196l-2.397 2.397L3.5 24L24 3.5l12.593 12.593l-2.216 2.216m-2.773 2.773l-3.791 3.791m-2.94 2.94l-3.675 3.675");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
