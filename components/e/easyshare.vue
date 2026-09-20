<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="wh-rb6bhx"/><path class="ni0zrgbqv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:easyshare" /></template>
<style>
.ni0zrgbqv {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M20.194 24c0-4.186 3.426-7.611 7.612-7.611h9.083c4.186 0 7.611 3.425 7.611 7.611s-3.425 7.611-7.611 7.611h-9.083a7.55 7.55 0 0 1-3.807-1.027");
}

.wh-rb6bhx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M27.806 24c0 4.186-3.426 7.611-7.612 7.611h-9.083C6.925 31.611 3.5 28.186 3.5 24s3.425-7.611 7.611-7.611h9.083c1.384 0 2.685.374 3.807 1.027");
}

</style>
