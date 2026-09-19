<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="z16zgab8f"/><path class="hm3xf7bbj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:buildings-for-minecraft-pe" /></template>
<style>
.hm3xf7bbj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M17.833 8.583v3.083H14.75v3.084h-3.083v3.083H8.583M24 20.917h-3.083V24");
}

.z16zgab8f {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M5.5 24v-3.083h3.083V14.75h3.084v-3.083h3.083V8.583h6.167V5.5H24v3.083h3.083v3.084h2.706v3.083h-2.706v3.083H24v3.084h3.083V24h3.084v3.083h3.083v3.084h3.083v3.083h3.195v3.083H42.5V42.5h-6.167v-3.083H33.25v-3.084h-3.083V33.25h-3.084v-3.083H24v-3.084h-3.083V24h-3.084v3.083H14.75v3.084h-3.083v-3.084H8.583V24z");
}

</style>
