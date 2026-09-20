<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rvpatpb-y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:escalator-warning-outline-rounded" /></template>
<style>
.rvpatpb-y {
  fill: currentColor;
  d: path("M6.309 5.307q-.501-.501-.501-1.191t.5-1.192T7.5 2.423t1.191.501t.501 1.192t-.5 1.19q-.502.502-1.192.502t-1.191-.501m10.345 6q-.529 0-.918-.379q-.39-.38-.39-.928q0-.567.39-.937q.389-.37.918-.37q.567 0 .937.37t.37.937q0 .548-.37.928t-.937.38M5.73 20.692v-5.769h-.846q-.348 0-.578-.23t-.23-.577V9.039q0-.672.472-1.144t1.143-.472h2.923q.512 0 .914.282t.58.757l2.499 6.598l2.294-2.294q.18-.185.403-.283q.222-.098.482-.098h1.982q.51 0 .87.36q.361.36.361.87v2.654q0 .343-.247.544q-.247.2-.56.264H18v3.615q0 .349-.23.578t-.578.23h-1.076q-.349 0-.578-.23t-.23-.578v-6.907l-1.712 1.661q-.106.123-.26.185q-.155.061-.303.061h-.804q-.256 0-.44-.134q-.183-.135-.27-.36L9.5 9.658v11.034q0 .349-.23.578t-.578.23H6.538q-.348 0-.578-.23t-.23-.578");
}

</style>
