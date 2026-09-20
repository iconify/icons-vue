<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="e7thu-qur"/><path class="yntieubns"/><path class="jkxqtjbyp"/><path class="wdcolkbun"/><path class="k-77q8bth"/><path class="w9-bqiusn"/><path class="cu028nc_o"/><path class="csnow12hv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noto-v1:briefcase" /></template>
<style>
.csnow12hv {
  fill: none;
  stroke: var(--svg-color--795548, #795548);
  stroke-linecap: round;
  stroke-miterlimit: 10;
  stroke-width: var(--svg-stroke-width--6px, 6px);
  d: path("M82.89 24.64c-2.97-5.79-10.3-9.89-18.89-9.89s-15.92 4.1-18.89 9.89");
}

.cu028nc_o {
  fill: var(--svg-color--757575, #757575);
  d: path("M74.31 74.43v1.93c0 .89-.72 1.6-1.6 1.6H55.29c-.89 0-1.6-.72-1.6-1.6v-1.93c0-.89.72-1.6 1.6-1.6h17.42c.89 0 1.6.72 1.6 1.6");
}

.e7thu-qur {
  fill: none;
  stroke: var(--svg-color--bdbdbd, #bdbdbd);
  stroke-miterlimit: 10;
  stroke-width: var(--svg-stroke-width--4px, 4px);
  d: path("M84.3 30.37c0-2.02-.51-3.95-1.42-5.73m-37.77 0c-.91 1.77-1.42 3.71-1.42 5.73");
}

.jkxqtjbyp {
  fill: var(--svg-color--5d4037, #5d4037);
  d: path("M114.36 38.88H13.64c-3.59 0-6.5 2.77-6.5 6.19V69.8c0 .98.52 1.88 1.37 2.43C21.14 80.39 42.73 84.83 64 85.24c21.27-.41 42.86-4.85 55.49-13.01c.85-.55 1.37-1.45 1.37-2.43V45.06c0-3.41-2.91-6.18-6.5-6.18");
}

.k-77q8bth {
  fill: var(--svg-color--757575, #757575);
  d: path("M72.31 74.77v15.69c0 .89-.72 1.6-1.6 1.6H57.29c-.89 0-1.6-.72-1.6-1.6V74.77c0-.89.72-1.6 1.6-1.6h13.42c.89 0 1.6.72 1.6 1.6");
}

.w9-bqiusn {
  fill: var(--svg-color--bdbdbd, #bdbdbd);
  d: path("M72.31 71.33v15.69c0 .89-.72 1.6-1.6 1.6H57.29c-.89 0-1.6-.72-1.6-1.6V71.33c0-.89.72-1.6 1.6-1.6h13.42c.89 0 1.6.72 1.6 1.6");
}

.wdcolkbun {
  fill: var(--svg-color--795548, #795548);
  d: path("M116.01 30.37H11.99c-3.71 0-6.71 3-6.71 6.71V63.9c0 1.06.54 2.04 1.41 2.63C19.74 75.37 42.04 80.19 64 80.63c21.96-.44 44.26-5.26 57.31-14.1c.88-.59 1.41-1.57 1.41-2.63V37.08c0-3.71-3.01-6.71-6.71-6.71");
}

.yntieubns {
  fill: var(--svg-color--795548, #795548);
  d: path("M15.04 33.97h97.93c4.36 0 7.9 3.54 7.9 7.9v66.06c0 4.36-3.54 7.9-7.9 7.9H15.04c-4.36 0-7.9-3.54-7.9-7.9V41.87c0-4.36 3.53-7.9 7.9-7.9");
}

</style>
