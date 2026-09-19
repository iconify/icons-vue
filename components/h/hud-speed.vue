<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="dpyctnb6k"/><path class="h8hbq_biu"/><circle class="q501u37aj"/><path class="yi0sftbie"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:hud-speed" /></template>
<style>
.dpyctnb6k {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m29.748 20.537l-4.001 6.045m2.006-6.974a2.62 2.62 0 0 1 2.618 2.618v2.667a2.62 2.62 0 0 1-2.618 2.618h0a2.62 2.62 0 0 1-2.618-2.618v-2.667a2.62 2.62 0 0 1 2.618-2.618");
}

.h8hbq_biu {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M4.5 20.675c11.084-9.981 27.916-9.981 39 0M13.024 34.801a21.24 21.24 0 0 1 21.239 0m9.236-14.126L34.265 34.81M4.5 20.675l8.526 14.136");
}

.q501u37aj {
  cx: 20.542px;
  cy: 24.893px;
  r: 2.618px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.yi0sftbie {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M22.932 20.576c-.436-.571-1.1-.964-2.203-.964h-.184a2.617 2.617 0 0 0-2.617 2.618v2.667");
}

</style>
