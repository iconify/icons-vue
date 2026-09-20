<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xe4v_w8ec"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:escalator-warning" /></template>
<style>
.xe4v_w8ec {
  fill: currentColor;
  d: path("M6.309 5.307q-.501-.501-.501-1.191t.5-1.192T7.5 2.423t1.191.501t.501 1.192t-.5 1.19q-.502.502-1.192.502t-1.191-.501m10.345 6q-.529 0-.918-.379q-.39-.38-.39-.928q0-.567.39-.937q.389-.37.918-.37q.567 0 .937.37t.37.937q0 .548-.37.928t-.937.38M5.73 21.5v-6.577H4.077V9.039q0-.672.472-1.144t1.143-.472h2.923q.512 0 .914.282t.58.757l2.499 6.598l2.294-2.294q.18-.185.403-.283q.222-.098.482-.098h1.982q.51 0 .87.36q.361.36.361.87v3.462h-1V21.5h-2.692v-7.715l-1.93 1.907h-1.68L9.5 9.658V21.5z");
}

</style>
