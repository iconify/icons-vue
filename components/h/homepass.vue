<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="anu-59bss"/><path class="p6paz43la"/><path class="k5fl0b9aw"/><path class="grl-ag85o"/><path class="g_ygjqwfo"/><path class="api-fdbvb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:homepass" /></template>
<style>
.anu-59bss {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M13.25 5.373L6.161 17.651c-.306.63-.457 1.44-.096 2.046l6.697 11.62c.357.618.997.849 1.59.849h11.324");
}

.api-fdbvb {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M13.25 42.61h14.178c.698-.05 1.475-.324 1.82-.94l6.714-11.61c.357-.618.236-1.288-.06-1.8l-5.662-9.807");
}

.g_ygjqwfo {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m34.717 42.627l7.089-12.278c.306-.629.457-1.438.096-2.045l-6.697-11.62c-.357-.619-.997-.849-1.59-.849H22.291");
}

.grl-ag85o {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m45.5 23.991l-7.089-12.278c-.392-.58-1.017-1.115-1.723-1.105l-13.413-.01c-.713 0-1.233.439-1.53.952l-5.661 9.806");
}

.k5fl0b9aw {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M34.75 5.373H20.572c-.698.05-1.475.323-1.819.94l-6.715 11.61c-.357.617-.236 1.287.06 1.8l5.662 9.807");
}

.p6paz43la {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M2.5 23.991L9.589 36.27c.392.58 1.017 1.116 1.723 1.106l13.413.01c.714 0 1.233-.439 1.53-.952l5.661-9.807");
}

</style>
