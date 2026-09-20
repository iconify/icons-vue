<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="mo5_47bdx"/><path class="n4tpedcaf"/><rect class="j3s9ivbxi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:dhgate" /></template>
<style>
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

.mo5_47bdx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M14.866 19.15v6.878m4.557-6.878v6.878m-4.557-3.525h4.557m6.564-3.317v7.312a2.445 2.445 0 0 1-2.437 2.438c-.732 0-1.341-.244-1.707-.731");
}

.n4tpedcaf {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M23.55 19.064za2.445 2.445 0 0 1 2.437 2.438v1.584a2.445 2.445 0 0 1-2.437 2.437a2.445 2.445 0 0 1-2.438-2.437v-1.584a2.445 2.445 0 0 1 2.438-2.438m10.12.946v5.159c0 .515.343.86.859.86h.258m-2.063-4.643h1.891m-3.5 2.923c0 .946-.774 1.72-1.72 1.72a1.725 1.725 0 0 1-1.719-1.72V23.19c0-.945.774-1.72 1.72-1.72c.945 0 1.72.775 1.72 1.72m0 2.837v-4.642M8.5 26.028V19.15h1.548c1.634 0 3.01 1.376 3.01 3.01v.86c0 1.633-1.376 3.008-3.01 3.008zm30.743-.86c-.258.516-.86.86-1.462.86a1.725 1.725 0 0 1-1.72-1.72V23.19c0-.946.774-1.72 1.72-1.72s1.719.774 1.719 1.72v.602h-3.438");
}

</style>
