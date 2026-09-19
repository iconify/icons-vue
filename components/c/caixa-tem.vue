<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="n1nhmybij"/><ellipse class="ki5h1edmu"/><path class="rpgkqohxy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:caixa-tem" /></template>
<style>
.ki5h1edmu {
  cx: 18.273px;
  cy: 18.699px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 3.029px;
  ry: 3.408px;
}

.n1nhmybij {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 7.387C13.23 7.387 4.5 14.825 4.5 24a14.83 14.83 0 0 0 3.147 9.045L4.5 40.613l9.116-2.554A21.94 21.94 0 0 0 24 40.613c10.77 0 19.5-7.438 19.5-16.613S34.77 7.387 24 7.387m1.988 11.312h6.342");
}

.rpgkqohxy {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 34.839c5.064 0 10.495-4.307 10.495-10.082c-4.023 4.07-7.087 4.686-10.495 4.686s-6.531-.615-10.555-4.686c0 5.775 5.49 10.082 10.555 10.082");
}

</style>
