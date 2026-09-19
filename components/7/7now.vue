<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ixh0l1bfp"/><path class="r32g-wbft"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:7now" /></template>
<style>
.ixh0l1bfp {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M18.4 32c-.4 3.8-.5 7.7-.2 11.5h10.9c.2-3.9.2-7.8.4-11.5m1.7-9.5c1.2-3.5 3.7-6.5 7-8.2V4.5c-6.4 3.1-14.3 8.3-17.7 18");
}

.r32g-wbft {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M12.9 4.5v8.9H26c3.1-3.9 8.1-6.6 12.3-8.9zm2.5 25.6v-5.6l3.7 5.6v-5.6m13.1 0l-1.4 5.6l-1.4-5.6l-1.4 5.6l-1.4-5.6m-5.2 3.7c0 1 .8 1.9 1.8 1.9s1.9-.8 1.9-1.9v-1.9c0-1-.8-1.9-1.9-1.9s-1.8.8-1.8 1.9z");
}

</style>
