<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="b2dwellur"/><path class="ork163bgo"/><path class="caqy__3mw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:dualwallpaper" /></template>
<style>
.b2dwellur {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M9.427 34.312v4.695q0 3.493 3.139 3.493h17.16q3.14 0 3.14-3.493V14.753q0-3.493-3.14-3.493h-17.16q-3.14 0-3.14 3.493z");
}

.caqy__3mw {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M21.14 22.074c2.668 0 4.827 2.155 4.827 4.806c0 2.663-2.16 4.806-4.827 4.806a4.807 4.807 0 0 1-4.814-4.806a4.815 4.815 0 0 1 4.814-4.806m0-4.757V20.6m0 12.709v3.282m-6.39-9.711h-3.276m19.319 0h-3.288m-13.289 6.887l2.333-2.316m9.108-9.031l2.32-2.316m-11.317 2.18l-2.332-2.316m13.649 13.799l-2.32-2.316");
}

.ork163bgo {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M15.06 11.074V9.055q0-3.493 3.152-3.493h4.702l7.792-.062h4.703q3.165 0 3.14 3.48v4.708l.024 15.508v4.695q0 3.135-3.5 3.134h-2.022");
}

</style>
