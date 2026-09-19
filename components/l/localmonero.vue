<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="y9tr6bcfx"><path class="ami2mnkty"/><path class="f20_3_wyr"/></g><path class="ky_er68qs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:localmonero" /></template>
<style>
.ami2mnkty {
  d: path("M13.383 28.418h4.322v-8.836L24 26.407l6.29-6.825v8.836h4.328");
}

.f20_3_wyr {
  d: path("M35.5 24c0 6.351-5.149 11.5-11.5 11.5S12.5 30.351 12.5 24S17.65 12.5 24 12.5S35.5 17.65 35.5 24");
}

.ky_er68qs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M3.5 24L13.75 6.246h20.5L44.5 24L34.25 41.754h-20.5z");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
