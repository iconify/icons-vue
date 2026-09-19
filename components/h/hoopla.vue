<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="a8nxw9tnq"/><rect class="j3s9ivbxi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:hoopla" /></template>
<style>
.a8nxw9tnq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M9.501 18.745v8.085M9.5 23.495c0-1.112.896-2.021 1.99-2.021s1.988.91 1.988 2.02v3.336m3.812.01c-1.094 0-1.99-.91-1.99-2.02v-1.315c0-1.111.896-2.02 1.99-2.02s1.988.909 1.988 2.02v1.314c0 1.112-.895 2.021-1.989 2.021m5.8-.001c-1.094 0-1.989-.91-1.989-2.021v-1.314c0-1.112.895-2.021 1.989-2.021s1.988.91 1.988 2.02v1.315c0 1.111-.895 2.02-1.988 2.02m3.811-2.026c0 1.112.895 2.021 1.989 2.021s1.989-.909 1.989-2.02v-1.314c0-1.112-.895-2.022-1.99-2.022s-1.988.91-1.988 2.021m0-2.021v8.085m5.8-10.8v8.085m5.8-2.023c0 1.111-.894 2.02-1.988 2.02s-1.988-.909-1.988-2.02V23.51c0-1.112.894-2.022 1.988-2.022s1.989.91 1.989 2.022m0 3.335v-5.357");
}

.j3s9ivbxi {
  width: 37px;
  height: 37px;
  x: 5.5px;
  y: 5.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 4px;
  ry: 4px;
}

</style>
