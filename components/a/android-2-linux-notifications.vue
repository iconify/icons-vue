<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="cpk0fnbgt"/><path class="zmrmqowos"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:android-2-linux-notifications" /></template>
<style>
.cpk0fnbgt {
  cx: 24px;
  cy: 24px;
  r: 21.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.zmrmqowos {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M28.061 22.151v9.421h4.71m2.91.001v-9.421l6.242 9.421v-9.421m-26.814-.71a5.023 5.023 0 0 1 6.014-4.922c2.104.405 3.784 2.225 3.994 4.357c.156 1.587-.346 3.152-1.442 4.114c-2.03 1.781-8.566 6.582-8.566 6.582h10.036m-13.976-3.151H7.087M6.07 31.545l3.062-9.393l3.062 9.421");
}

</style>
