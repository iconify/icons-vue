<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="cyj-8ompy"/><circle class="yocrk4bhn"/><path class="x_5-54bhp"/><path class="xvlow8b5v"/><path class="wt_7aoa_j"/><path class="o49-vibqy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:door" /></template>
<style>
.cyj-8ompy {
  fill: var(--svg-color--bf6952, #bf6952);
  d: path("M29 34a2 2 0 0 1-2 2H9a2 2 0 0 1-2-2V2a2 2 0 0 1 2-2h18a2 2 0 0 1 2 2z");
}

.o49-vibqy {
  fill: var(--svg-color--854836, #854836);
  d: path("M11 26a1 1 0 0 1-1-1v-3a1 1 0 0 1 1-1h14a1 1 0 0 1 0 2H12v2a1 1 0 0 1-1 1m0-11a1 1 0 0 1-1-1V4a1 1 0 0 1 1-1h14a1 1 0 0 1 0 2H12v9a1 1 0 0 1-1 1");
}

.wt_7aoa_j {
  fill: var(--svg-color--ac5640, #ac5640);
  d: path("M25 21a1 1 0 0 1 1 1v3a1 1 0 0 1-1 1H11a1 1 0 0 1 0-2h13v-2a1 1 0 0 1 1-1");
}

.x_5-54bhp {
  fill: var(--svg-color--ac5640, #ac5640);
  d: path("M25 3a1 1 0 0 0-1 1v9H11a1 1 0 0 0 0 2h14a1 1 0 0 0 1-1V4a1 1 0 0 0-1-1m0 25a1 1 0 0 1 1 1v3a1 1 0 0 1-1 1H11a1 1 0 0 1 0-2h13v-2a1 1 0 0 1 1-1");
}

.xvlow8b5v {
  fill: var(--svg-color--854836, #854836);
  d: path("M11 33a1 1 0 0 1-1-1v-3a1 1 0 0 1 1-1h14a1 1 0 0 1 0 2H12v2a1 1 0 0 1-1 1");
}

.yocrk4bhn {
  cx: 11px;
  cy: 18px;
  r: 1.5px;
  fill: var(--svg-color--ffac33, #ffac33);
}

</style>
