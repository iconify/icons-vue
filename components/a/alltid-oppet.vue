<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="dzrm-y4_a"/><path class="e81eiibot"/><path class="kr_zsac6f"/><path class="tmkhmkb7i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:alltid-oppet" /></template>
<style>
.dzrm-y4_a {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 8.813h-.1c-4.7-4.7-12.3-4.7-16.9 0c-4.7 4.7-4.7 12.3 0 16.9h0l17 17l17-17c4.7-4.7 4.7-12.3 0-16.9s-12.4-4.7-17 0");
}

.e81eiibot {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M33.7 25.013h-3c-1.6 0-2.8-1.3-2.8-2.8v-10");
}

.kr_zsac6f {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M33.7 27.713h-3.1c-2.9 0-5.3-2.4-5.3-5.3v-10.1m-11.2 12.7h3c1.6 0 2.8-1.3 2.8-2.8v-10");
}

.tmkhmkb7i {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M14.1 27.713h3.1c2.9 0 5.3-2.4 5.3-5.3v-10.1");
}

</style>
