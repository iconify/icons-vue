<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="yyyqymv8p"/><path class="k8g_tcc6b"/><rect class="mredrfbji"/><circle class="ajzzl5bvb"/><path class="cem0c_whr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:db-casino" /></template>
<style>
.ajzzl5bvb {
  cx: 27.022px;
  cy: 31.543px;
  r: 0.75px;
  fill: currentColor;
}

.cem0c_whr {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M27.022 34.474v6.341m-6.473-.535c.437.367.908.535 1.968.535h.536c.874 0 1.582-.71 1.582-1.585s-.708-1.585-1.582-1.585H21.98c-.874 0-1.582-.71-1.582-1.585c0-.876.708-1.586 1.582-1.586h.537c1.059 0 1.53.168 1.967.535M10.97 39.61a2.393 2.393 0 0 1-4.47-1.187v-1.556a2.392 2.392 0 0 1 4.468-1.192m6.95 2.748a2.393 2.393 0 0 1-4.785 0v-1.556a2.393 2.393 0 0 1 4.785 0m0 3.948v-6.341m16.375 6.338v-3.948a2.393 2.393 0 0 0-4.785 0m-.001 3.948v-6.341");
}

.k8g_tcc6b {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M12.71 25.814V10.007h2.935a7.903 7.903 0 0 1 0 15.806zm18.629-7.904h-5.08m5.08 0a3.952 3.952 0 0 1 0 7.904h-5.08V10.007h5.08a3.952 3.952 0 0 1 0 7.903");
}

.mredrfbji {
  width: 4.785px;
  height: 6.341px;
  x: 36.715px;
  y: 34.474px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 2.393px;
  ry: 2.393px;
}

.yyyqymv8p {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M39.242 26.378V9.443a2.26 2.26 0 0 0-2.258-2.258H11.016a2.26 2.26 0 0 0-2.258 2.258v16.935a2.26 2.26 0 0 0 2.258 2.259h25.968a2.26 2.26 0 0 0 2.258-2.259");
}

</style>
