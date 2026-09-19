<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="cm51apnqh"/><path class="e4r2qeblw"/><path class="r6xd7plya"/><path class="mlwkhlbyu"/><path class="mwavo-t9n"/><path class="jwz_-zj2g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:baac-tree-bank" /></template>
<style>
.cm51apnqh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M19.542 30.215c-.408 4.662-2.662 10.491-6.268 11.818c3.638.743 7.697.251 10.107-1.945");
}

.e4r2qeblw {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M31.676 19.76c-8.972 0-12.152 5.25-12.152 11.222l-.001.001c0 6.36 4.452 11.517 9.942 11.517c2.507 0 4.922-1.097 6.76-3.072a8.6 8.6 0 0 1-1.977.23c-5.49 0-9.942-5.84-9.942-11.519c0-2.943.84-5.88 3.09-7.9");
}

.jwz_-zj2g {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M30.258 15.723c1.633-2.175 1.786-5.764.338-7.428c-3.543.83-5.836 3.119-6.223 6.146");
}

.mlwkhlbyu {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M16.704 14.23c3.025 1.917 5.986 4.89 7.365 7.39m1.757-.883c.377-5.928 8.754-6.917 13.778-2.81c-3.269 5.857-9.738 7.785-13.664 4.022");
}

.mwavo-t9n {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M27.76 13.733c-1.255 1.481-1.768 2.801-1.765 4.518");
}

.r6xd7plya {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M25.393 20.919c.478-9.54-6.62-15.212-16.707-15.419c-2.08 11.41 7.511 18.966 14.146 17.055");
}

</style>
