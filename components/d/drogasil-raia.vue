<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="n9z37pdzm"/><path class="d0tx80zzd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:drogasil-raia" /></template>
<style>
.d0tx80zzd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M30.706 15.367a2 2 0 0 1 2-2h0m-2 0v5.3");
}

.n9z37pdzm {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M16.123 25.938L4.12 25.684a.607.607 0 0 0-.442 1.036l17.601 17.6a.607.607 0 0 0 1.036-.441l-.254-12.002a6.07 6.07 0 0 0-5.94-5.939m15.756-3.876l12.002.254a.607.607 0 0 0 .442-1.036L26.72 3.68a.607.607 0 0 0-1.036.441l.254 12.002a6.07 6.07 0 0 0 5.94 5.939m-9.816-5.939l.254-12.002a.607.607 0 0 0-1.036-.442L3.68 21.28a.607.607 0 0 0 .441 1.036l12.002-.254a6.07 6.07 0 0 0 5.939-5.94m3.876 15.755l-.254 12.002a.607.607 0 0 0 1.036.442l17.6-17.601a.607.607 0 0 0-.441-1.036l-12.002.254a6.07 6.07 0 0 0-5.939 5.94");
}

</style>
