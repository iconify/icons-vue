<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gy9ehlidy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:formula-dispenser" /></template>
<style>
.gy9ehlidy {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("m6.386 2.759l6.5-1q.057-.009.114-.009h5q.074 0 .146.014q.073.015.141.043t.13.069q.061.041.113.094q.053.052.094.113t.069.13t.043.141t.014.146q0 1.772-.548 2.815q1.548.318 1.548 2.185q0 2.128-2.013 2.243q1.013 1.169 1.013 2.757V18q0 1.76-1.245 3.005T14.5 22.25h-5q-1.76 0-3.005-1.245T5.25 18v-5.5q0-1.588 1.013-2.757Q4.25 9.628 4.25 7.5q0-2.25 2.25-2.25h6.265q-.377-.757-.478-1.881l-5.673.872q-.147.023-.292-.013t-.266-.123q-.12-.088-.197-.216t-.1-.275q-.012-.073-.008-.147q.003-.074.021-.145q.017-.072.048-.139q.032-.067.075-.127q.044-.059.098-.109t.118-.088t.133-.064t.142-.036m10.828.491h-3.428q.178 1.703 1.231 2h.966q1.053-.297 1.231-2");
}

</style>
