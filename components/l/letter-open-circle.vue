<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":26,"height":26};
const content = `<g class="ft5dv1b6b"><path class="njphh7bdc"/><path class="nev1bwteq"/><path class="j9zsp8bsl"/><path clip-rule="evenodd" class="s401rdvdc"/><path clip-rule="evenodd" class="tbs8bv5jq"/><path clip-rule="evenodd" class="oq6qes85s"/><path clip-rule="evenodd" class="ksag4bb-q"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons-pop:letter-open-circle" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.j9zsp8bsl {
  stroke: currentColor;
  stroke-linecap: round;
  d: path("M10 11h6m-5.5 2h5");
}

.ksag4bb-q {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M13 24c6.075 0 11-4.925 11-11S19.075 2 13 2S2 6.925 2 13s4.925 11 11 11m0 2c7.18 0 13-5.82 13-13S20.18 0 13 0S0 5.82 0 13s5.82 13 13 13");
}

.nev1bwteq {
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("m13 17.5l-6.5-4.33V8.5h13v4.67zm-4.5-9l4.5-3l4.5 3");
}

.njphh7bdc {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M20.5 11.5v9h-15v-9");
}

.oq6qes85s {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M12.445 4.668a1 1 0 0 1 1.11 0l4.5 3l-1.11 1.664L13 6.702l-3.945 2.63l-1.11-1.664zM9.5 11a.5.5 0 0 1 .5-.5h6a.5.5 0 0 1 0 1h-6a.5.5 0 0 1-.5-.5m.5 2a.5.5 0 0 1 .5-.5h5a.5.5 0 0 1 0 1h-5a.5.5 0 0 1-.5-.5");
}

.s401rdvdc {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M5.5 10.5a1 1 0 0 1 1 1v8h13v-8a1 1 0 1 1 2 0v9a1 1 0 0 1-1 1h-15a1 1 0 0 1-1-1v-9a1 1 0 0 1 1-1");
}

.tbs8bv5jq {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M5.5 8.5a1 1 0 0 1 1-1h13a1 1 0 0 1 1 1v4.67a1 1 0 0 1-.446.832l-6.5 4.33a1 1 0 0 1-1.108 0l-6.5-4.33a1 1 0 0 1-.446-.832zm2 1v3.135l5.5 3.663l5.5-3.663V9.5z");
}

</style>
