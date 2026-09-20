<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="wvi4alb6o"/><path class="zkrwjklrl"/><circle class="tokixl7-j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:blur" /></template>
<style>
.tokixl7-j {
  cx: 8.597px;
  cy: 24px;
  r: 4.097px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.wvi4alb6o {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M15.834 37.463V10.537m0 0H27.11a6.724 6.724 0 0 1 6.717 6.732A6.724 6.724 0 0 1 27.11 24H15.834");
}

.zkrwjklrl {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M12.669 24H27.11a6.724 6.724 0 0 1 6.717 6.732a6.724 6.724 0 0 1-6.717 6.731H15.834M27.11 24H43.5m0 0v-4.683M38.817 24v-4.683");
}

</style>
