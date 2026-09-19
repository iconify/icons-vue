<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="fhn-lv1-v"/><path class="s7fpvo7ii"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:commbank" /></template>
<style>
.fhn-lv1-v {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m24.363 3.863l20.5 20.5l-20.5 20.499l-20.5-20.5z");
}

.s7fpvo7ii {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m39.53 19.03l-7.417 7.416l-7.75 18.417");
}

</style>
