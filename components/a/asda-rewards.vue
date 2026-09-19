<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="i6x4-lbsb"/><path class="pgt5-4bav"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:asda-rewards" /></template>
<style>
.i6x4-lbsb {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M32.722 30.581H15.279M10.959 43.5L24 4.5l13.041 39");
}

.pgt5-4bav {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m24 17.298l1.99 3.688l3.74.648l-2.422 2.964l1.053 4.554l-4.102-2.07l-3.688 2.07l.34-4.554l-2.737-2.676l3.752-.937z");
}

</style>
