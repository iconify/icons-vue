<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ll0g54h-q"/><path class="ift9wsbek"/><circle class="e9we-z1ad"/><circle class="z1nr98bef"/><path class="l5dqn92xo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:busto" /></template>
<style>
.e9we-z1ad {
  cx: 36.373px;
  cy: 31.007px;
  r: 3.89px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.ift9wsbek {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M42.135 12.856H12.641v20.663h20.76m6.1 0h2.947");
}

.l5dqn92xo {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M39.5 33.52h2.947zm-19.723 0a3.89 3.89 0 0 0 2.967 1.377a3.89 3.89 0 0 0 2.965-1.377M12.64 12.856h-2.468v5.772s.089 1.653 2.284 1.653m15.545-7.425v20.592M12.874 29.65h14.921m.459-5.473h14.06m-3.694-.099V13.19m-10.619-.334h-2.468v5.772s.089 1.653 2.284 1.653m-15.193 7.41h3.597s1.92.121 1.92 1.92m9.853-1.92h-3.597s-1.92.121-1.92 1.92");
}

.ll0g54h-q {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.5 5.5h-29c-2.2 0-4 1.8-4 4v29c0 2.2 1.8 4 4 4h29c2.2 0 4-1.8 4-4v-29c0-2.2-1.8-4-4-4");
}

.z1nr98bef {
  cx: 36.373px;
  cy: 31.007px;
  r: 1.778px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
