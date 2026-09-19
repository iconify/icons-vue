<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="tfz__cc-z"/><path class="kqt8p567v"/><path class="b_xaiz18j"/><path class="hnp1m8ikn"/><ellipse transform="rotate(-23.695 39.33 28.26)" class="w96wlzbij"/><ellipse transform="rotate(-66.305 8.67 28.26)" class="vkyezebgr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:dcss" /></template>
<style>
.b_xaiz18j {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M10.911 36.386A3.3 3.3 0 0 0 9.572 38.6c.021 1.21-1.884 1.49-1.568 2.355a2.16 2.16 0 0 0 2.408 1.546c1.586 0 1.764-1.379 1.804-2.084s1.628-.826 1.72-2.563m9.918-15.287s-.325 2.902.938 3.052c1.28.152.96 3.227 1.437 4.312c.949 2.157 3.078-1.157 3.074-3.898c-.004-2.695.696-1.168.944-3.9m6.841 14.253a3.3 3.3 0 0 1 1.34 2.213c-.022 1.21 1.884 1.49 1.567 2.355a2.16 2.16 0 0 1-2.407 1.546c-1.587 0-1.765-1.379-1.805-2.084s-1.627-.826-1.72-2.563M9.845 19.551c1.168-2.243 7.06-3.95 14.155-3.95a39 39 0 0 1 7.09.62m6.245 2.371a3.2 3.2 0 0 1 .804.93m-5.465-1.662s4.158-12.238 7.624-12.357s1.673 4.143.231 5.303s-5.388 8.22-5.388 8.22a1.72 1.72 0 0 1-2.467-1.166");
}

.hnp1m8ikn {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M39.525 17.856a5.85 5.85 0 0 1-.707 3.825a1.1 1.1 0 0 0-.171.644m.282 12.25c-2.216 2.944-5.961 4.39-14.929 4.39");
}

.kqt8p567v {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M8.475 17.856a5.85 5.85 0 0 0 .706 3.825a1.1 1.1 0 0 1 .172.644m-.282 12.25c2.216 2.943 5.96 4.39 14.929 4.39");
}

.tfz__cc-z {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.899 15.831a2.27 2.27 0 0 1 .694 1.54c0 2.87-6.981 5.197-15.593 5.197S8.407 20.241 8.407 17.37S15.388 12.172 24 12.172a42 42 0 0 1 7.585.655");
}

.vkyezebgr {
  cx: 8.67px;
  cy: 28.26px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 3.913px;
  ry: 2.979px;
}

.w96wlzbij {
  cx: 39.33px;
  cy: 28.259px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 2.979px;
  ry: 3.913px;
}

</style>
