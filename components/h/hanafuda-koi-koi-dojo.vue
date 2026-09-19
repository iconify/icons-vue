<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="st0yi1h4g"/><path class="g90ja3b4i"/><path class="rprogvscj"/><path class="n-8u872hz"/><circle class="invtlk-9y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:hanafuda-koi-koi-dojo" /></template>
<style>
.g90ja3b4i {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m14.628 41.987l9.036-3.349l13.219 2.269L42.5 9.308L23.217 5.905l-5.456 31.437l5.903 1.296");
}

.invtlk-9y {
  cx: 27.558px;
  cy: 24.993px;
  r: 0.75px;
  fill: currentColor;
}

.n-8u872hz {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m13.512 13.41l1.98 27.335l5.348-2.431m4.482.49l.229-10.66s4.433 0 4.66-1.818s8.075-4.431 8.075-4.431l-8.42 1.341s-.82-.15-1.268-.412c-.446-.26-5.131-1.022-5.885 2.536c-.819 3.874-.472 12.882-.472 12.882");
}

.rprogvscj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M14.628 42.096L5.5 17.842l8.102-3.188l-.323-4.482l8.912-.432");
}

.st0yi1h4g {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m22.191 11.604l-1.853 10.29a5.23 5.23 0 0 1-4.291-5.526a5.233 5.233 0 0 1 6.144-4.764m8.929-4.31c.5 5.86 4.4 10.68 9.57 12.18");
}

</style>
