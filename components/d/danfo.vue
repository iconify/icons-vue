<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="q_6g0b8lf"/><path class="mqz10tbnt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="logos:danfo" /></template>
<style>
.mqz10tbnt {
  fill: var(--svg-color--2e2e2e, #2e2e2e);
  d: path("M116.387 30.755c18.266-.275 36.438.501 54.052 8.177c40.133 17.492 65.051 59.935 60.148 103.434c-4.958 43.989-38.704 80.451-81.699 88.081c-5.283.937-10.702 1.525-16.062 1.551c-32.343.152-102.637-.349-102.637-.349V31.431h28.837l.009 171.791s48.808-.01 69.022-.213c39.38-.394 68.13-25.485 73.552-63.93c5.17-36.66-24.156-74.462-60.909-78.3c-7.755-.81-15.58-.958-24.16-1.457v86.128c5.382 0 10.511.413 15.548-.097c7.44-.753 12.217-6.458 12.31-14.393c.152-13.006.041-40.073.041-40.073c2.58.928 4.447 1.382 6.112 2.234c17.116 8.752 26.217 28.46 22.132 47.77c-3.885 18.364-20.145 32.584-39.105 33.362c-13.68.561-46.305.303-46.305.303l.194-143.83");
}

.q_6g0b8lf {
  fill: var(--svg-color--ffdf28, #ffdf28);
  d: path("M0 0h256v256H0z");
}

</style>
