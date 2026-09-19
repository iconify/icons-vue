<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="xa_s_djhq"/><ellipse class="ysxk7vbtw"/><ellipse class="if9e9lbcs"/><path class="p0su23b4h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:fantuan-delivery" /></template>
<style>
.if9e9lbcs {
  cx: 33.206px;
  cy: 23.947px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 2.228px;
  ry: 2.903px;
}

.p0su23b4h {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M14.699 41.125v-8.953h18.94v8.953");
}

.xa_s_djhq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24.106 6.876C14.023 6.876 4.5 21.16 4.5 31.982c0 5.659 4.867 9.143 8.467 9.143h22.066c5.194 0 8.467-4.646 8.467-9.143c0-11.15-9.143-25.106-19.384-25.106z");
}

.ysxk7vbtw {
  cx: 15.005px;
  cy: 23.947px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 2.228px;
  ry: 2.903px;
}

</style>
