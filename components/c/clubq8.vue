<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="cpk0fnbgt"/><path class="w-e8mniyk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:clubq8" /></template>
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

.w-e8mniyk {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M26.85 34.5a2 2 0 1 0 0 4h1.3a2 2 0 1 0 0-4m0 0a2 2 0 1 0 0-4h-1.3a2 2 0 1 0 0 4m0 0h1.3m-5 4l-2.65-2.618m0-5.382za2.65 2.65 0 0 1 2.65 2.65v2.7a2.65 2.65 0 1 1-5.3 0v-2.7a2.65 2.65 0 0 1 2.65-2.65m11.863-10a2.854 2.854 0 1 1 5.709 0v1.854a2.854 2.854 0 1 1-5.709 0m0 2.855V13.791m-8.144 3.854v4.71a2.854 2.854 0 1 0 5.709 0v-4.71m0 4.71v2.854m-10-11.419v9.992c0 .788.639 1.427 1.427 1.427h.428m-4.29-3.829v.047a3.782 3.782 0 1 1-7.565 0v-3.854a3.782 3.782 0 1 1 7.565 0v.048");
}

</style>
