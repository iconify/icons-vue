<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="odinllbwv"/><path class="wzj42r9nu"/><path class="eh7b7dgcx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:cleaner" /></template>
<style>
.eh7b7dgcx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M26.055 21.448C29.422 18.428 42.411 5.5 42.411 5.5M7.03 30.106c4.237.317 7.03-.612 7.03-.612m-3.142 7.893c6.19-.867 8.333-3.97 8.333-3.97");
}

.odinllbwv {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M11.732 38.242c4.055 3.835 7.865 4.258 7.865 4.258c3.178-2.839 4.91-5.375 6.842-10.807c0 0-7.548-7.321-9.091-9.625c0 0-3.509 1.8-6.223 2.048c-2.045.187-5.536-.86-5.536-.86c.028 2.918 2.023 11.088 6.143 14.986");
}

.wzj42r9nu {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M17.348 22.068c1.903-1.076 5.383-3.554 6.994-2.15a26 26 0 0 1 3.477 3.421c1.099 1.434-.418 5.077-1.38 8.354");
}

</style>
