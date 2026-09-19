<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="y9tr6bcfx"><path class="bola33set"/><path class="m-9rlhbwq"/></g><path class="xgz6wwc3e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:emoji-bunny" /></template>
<style>
.bola33set {
  d: path("M15.71 24.96c-1.633 3.53-9.143.706-9.143.706a1.38 1.38 0 0 1-.789-1.009l-.255-1.39a1.38 1.38 0 0 1 .175-.963l1.34-2.222a6.5 6.5 0 0 1 2.694-2.478l2.567-1.27s2.45-7.495 6.438-8.12c0 0 3.172 3.22-2.402 10.379c0 0 1.399.958 2.499 2.787c0 0 10.537-6.134 17.2 7.159c6.18 12.327-5.757 11.56-9.816 10.98c-1.028-.146-1.959-.76-2.393-1.705c-.454-.985-.357-2.157 2.312-2.5");
}

.m-9rlhbwq {
  d: path("M9.21 26.412c-.453 4.037 1.795 6.689 4.967 7.148c0 0 1.01 1.249 0 2.306c0 0-.933.807-1.69 1.558c-.875.869-.26 2.364.974 2.364h2.689c.474 0 .915-.243 1.168-.644l2.57-4.07l.867-2.74m16.966 1.224s5.354-2.184 4.575 2.668c-.665 4.143-5.79 1.575-5.79 1.575M10.877 17.038s-.278-1.304-.398-2.666c-.185-2.105.518-4.993 2.78-6.157c0 0 1.339-.161 2.184 2.201");
}

.xgz6wwc3e {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M23.8 36.34c-2.3.08-3.913-1.267-3.913-1.267");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
