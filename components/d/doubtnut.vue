<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="eiaj6e7lm"/><path class="exdo44nrt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:doubtnut" /></template>
<style>
.eiaj6e7lm {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M18.06 24.428a4.369 4.369 0 1 1-4.374 4.373a4.37 4.37 0 0 1 4.373-4.373M24.62 5.283l18.88 7.465m-5.998-2.125l-2.125 5.198a13.44 13.44 0 0 0-8.308-3.547l2.125-5.2m11.329 4.576l1.66 5.928");
}

.exdo44nrt {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M28.193 16.26h3.381l-.061 12.998a13.506 13.506 0 1 1-10.547-13.226v3.162a10.02 10.02 0 1 0 7.289 10.028Z");
}

</style>
