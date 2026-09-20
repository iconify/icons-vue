<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="lkg5--blf"/><circle class="q_1r_dsuu"/><circle class="h4z2acb-c"/><ellipse class="n051r1tqi"/><path class="ll25irb7s"/><path class="wkkvoy4al"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:flag-for-pirate-flag" /></template>
<style>
.h4z2acb-c {
  cx: 20.5px;
  cy: 12.5px;
  r: 1.5px;
  fill: var(--svg-color--31373d, #31373d);
}

.lkg5--blf {
  fill: var(--svg-color--31373d, #31373d);
  d: path("M32 5H4a4 4 0 0 0-4 4v18a4 4 0 0 0 4 4h28a4 4 0 0 0 4-4V9a4 4 0 0 0-4-4");
}

.ll25irb7s {
  fill: var(--svg-color--e6e7e8, #e6e7e8);
  d: path("M29.021 24.883a1 1 0 0 0-1.282.598L20.923 23l6.816-2.48a1 1 0 1 0 .598-1.282a1 1 0 1 0-1.281-.597L18 21.937l-9.056-3.296a.999.999 0 1 0-1.879-.684a1 1 0 0 0 .598 1.281a1 1 0 0 0-1.281.599a.999.999 0 1 0 1.879.683L15.077 23l-6.815 2.48a1 1 0 1 0-.598 1.281a1 1 0 1 0 1.281.598L18 24.065l9.055 3.295a1 1 0 1 0 1.281-.598a1 1 0 1 0 .685-1.879");
}

.n051r1tqi {
  cx: 18px;
  cy: 15.5px;
  fill: var(--svg-color--292f33, #292f33);
  rx: 1px;
  ry: 0.5px;
}

.q_1r_dsuu {
  cx: 15.5px;
  cy: 12.5px;
  r: 1.5px;
  fill: var(--svg-color--31373d, #31373d);
}

.wkkvoy4al {
  fill: var(--svg-color--e6e7e8, #e6e7e8);
  d: path("M18 7c-4 0-6 3.239-6 6c0 1.394.827 2.399 2 3.054V18a1 1 0 1 0 2 0v-1.216q.496.109 1 .162V18a1 1 0 1 0 2 0v-1.054q.504-.054 1-.162V18a1 1 0 1 0 2 0v-1.946c1.173-.654 2-1.659 2-3.054c0-2.761-2-6-6-6m-2.5 7c-.829 0-1.5 0-1.5-1.5a1.5 1.5 0 0 1 1.5-1.5c1.5 0 1.5.671 1.5 1.5s-.671 1.5-1.5 1.5m2.5 2c-.552 0-1-.224-1-.5s.448-.5 1-.5s1 .224 1 .5s-.448.5-1 .5m2.5-2c-.828 0-1.5-.671-1.5-1.5s0-1.5 1.5-1.5a1.5 1.5 0 0 1 1.5 1.5c0 1.5-.672 1.5-1.5 1.5");
}

</style>
