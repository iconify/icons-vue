<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ffnc2o_ww"/><path class="y72ylsb4u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:fedmobile" /></template>
<style>
.ffnc2o_ww {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m33.547 16.56l-1.052 5.926c-.263 1.48-1.706 2.678-3.224 2.677l-15.06-.013c-2.905-.003-6.27 1.923-6.655 4.09");
}

.y72ylsb4u {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M9.085 20.636c.385-2.167 3.75-4.093 6.654-4.09l22.35.019c1.517.001 2.96-1.197 3.224-2.677L42.5 7.204L13.59 7.18c-1.168-.001-2.278.92-2.48 2.06L5.5 40.813l7.941.007c1.751.002 3.417-1.381 3.72-3.089l2.235-12.578");
}

</style>
