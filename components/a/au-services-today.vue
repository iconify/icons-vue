<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ybg32l0ee"/><path class="iocpfkfek"/><path class="qrf0rac0c"/><path class="oyq4zp83h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:au-services-today" /></template>
<style>
.iocpfkfek {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m31.037 20.652l-1.122 4.042s-.874 2.664 1.1 2.664c2.321 0 2.954-2.874 2.954-2.874");
}

.oyq4zp83h {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M16.5 11h25c.554 0 1 .446 1 1v24c0 .554-.446 1-1 1h-25zm0 0L7 5.5v37l9.5-5.5m-7-17v8M7 5.5H5.5v37H7");
}

.qrf0rac0c {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m35.034 20.652l-1.44 5.237s-.21 1.414.804 1.391c1.362-.03 2.47-2.59 2.47-2.59m-8.807-4.038s-4.82-.727-5.816 4.246c-.88 4.392 3.728 1.739 4.376.99");
}

.ybg32l0ee {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m28.061 20.652l-1.44 5.237s-.496 1.496.838 1.496c1.54 0 2.456-2.691 2.456-2.691");
}

</style>
