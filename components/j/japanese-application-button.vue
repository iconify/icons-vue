<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="z5i8-q-yx"/><path class="o1kyagglw"/><path class="nws_l7bju"/><path class="m2_r0abwo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noto:japanese-application-button" /></template>
<style>
.m2_r0abwo {
  fill: var(--svg-color--ffbd52, #ffbd52);
  d: path("M39.7 12.9c0-2.3-1.6-3-10.8-2.7c-7.7.3-11.5 1.2-13.8 4s-2.9 8.5-3 15.3c0 4.8 0 9.3 2.5 9.3c3.4 0 3.4-7.9 6.2-12.3c5.4-8.7 18.9-10.6 18.9-13.6");
  opacity: var(--svg-opacity--0-75, 0.75);
}

.nws_l7bju {
  fill: var(--svg-color--fafafa, #fafafa);
  d: path("M63.6 109.2c-3.1 0-4.7-1.5-4.7-4.6V83.2H32.4c-1.9 0-3.4-.6-4.6-1.8S26 78.7 26 76.8V38.5c0-1.9.6-3.4 1.8-4.6s2.7-1.8 4.6-1.8H59v-8.2c0-3.1 1.6-4.6 4.7-4.6s4.6 1.5 4.6 4.6v8.2h27.6c1.9 0 3.4.6 4.6 1.8s1.8 2.7 1.8 4.6v38.3c0 1.9-.6 3.4-1.8 4.6s-2.7 1.8-4.6 1.8H68.2v21.4c0 3-1.5 4.6-4.6 4.6M34.9 53.1H59V40.9H37.3q-2.4 0-2.4 2.4zm2.4 21.4H59v-13H34.9v10.6q0 2.4 2.4 2.4m30.9-21.4h24.5v-9.9q0-2.4-2.4-2.4H68.2zm0 21.4h22.2q2.4 0 2.4-2.4V61.5H68.2z");
}

.o1kyagglw {
  fill: var(--svg-color--ff9800, #ff9800);
  d: path("M109.7 4H11.5C7.4 4 4 7.4 4 11.5v97.9c0 4.1 3.3 7.5 7.5 7.5h98.1c4.1 0 7.5-3.3 7.5-7.5V11.5c.1-4.1-3.1-7.4-7.2-7.5z");
}

.z5i8-q-yx {
  fill: var(--svg-color--f77e00, #f77e00);
  d: path("M116 4H12c-4.4 0-8 3.6-8 8v104c0 4.4 3.6 8 8 8h104c4.4 0 8-3.6 8-8V12c0-4.4-3.6-8-8-8");
}

</style>
