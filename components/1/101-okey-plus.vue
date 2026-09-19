<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="wwh-z5b0o"/><rect class="p3_ss2bim"/><path class="ncfwxnb3h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:101-okey-plus" /></template>
<style>
.ncfwxnb3h {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24.984 26.242v-4.484M22.742 24h4.483M38.5 5.5h-29a4 4 0 0 0-4 4v29a4 4 0 0 0 4 4h29a4 4 0 0 0 4-4v-29a4 4 0 0 0-4-4");
}

.p3_ss2bim {
  width: 9.741px;
  height: 14.704px;
  x: 20.113px;
  y: 16.648px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 4.87px;
  ry: 4.87px;
}

.wwh-z5b0o {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M12.5 16.648h3.676v14.704m15.648-14.704H35.5v14.704");
}

</style>
