<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="h16onhb4u"/><path class="zfnkg_cfu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:aethersx2" /></template>
<style>
.h16onhb4u {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M21.672 4.477L5.907 11.615a.37.37 0 0 0-.214.372l2.108 20.476a.49.49 0 0 0 .262.386l18.14 9.462a.37.37 0 0 0 .429-.058l12.722-11.87a.7.7 0 0 0 .22-.443l2.052-19.709a.315.315 0 0 0-.227-.335L22.168 4.44a.72.72 0 0 0-.496.037");
}

.zfnkg_cfu {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m5.798 11.902l21.005 7.667l-.308 22.76m14.993-32.113l-14.644 9.51");
}

</style>
