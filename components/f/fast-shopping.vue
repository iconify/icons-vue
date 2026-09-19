<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="ywgh7q4zn"/><circle class="spntc7byc"/><path class="bt_3l_hzj"/><circle class="fw7nq259a"/><path class="g1ih-mb5f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:fast-shopping" /></template>
<style>
.bt_3l_hzj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M4.5 10.805h4.678L13.856 34.5h17.899");
}

.fw7nq259a {
  cx: 37.5px;
  cy: 16.703px;
  r: 6px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.g1ih-mb5f {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M41.161 9.28L40.1 11.299m-7.583-2.375l4.017-1.526m.966 9.305l-1.271-3.661m-26.155 2.302l18.07.902M13.031 30.323h20.91c3.254 0 3.56-4.416 3.56-4.416m-26.345-5.084l18.005.508m-17.098 4.09l23.075.441m-4.604 4.461l.966-6.603m-6.763 6.603l-.153-14.255m-6.965-.347l1.49 14.602");
}

.spntc7byc {
  cx: 31.755px;
  cy: 37.551px;
  r: 3.051px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.ywgh7q4zn {
  cx: 13.856px;
  cy: 37.551px;
  r: 3.051px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
