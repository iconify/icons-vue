<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="cjn8w2exc"/><path class="iedaqf9gg"/><ellipse class="ujo3lnbds"/><ellipse class="bgxk540zg"/><path class="ibfbswlrb"/><path class="a86lmsb0q"/><path class="rgkf3zbyo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:duck-life-5" /></template>
<style>
.a86lmsb0q {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M28.331 17.013c.86-.59 1.648-.354 2.13.833c.283.702-.156 1.62-.935 2.348m-5.53 1.528q-.072-1.197.874-1.742q1.01-.579 2.287.437q1.109.881 0 1.02q-1.576.195-3.162.285m.665 3.284q-.098.673.666 1.293q1.095.273 2.142-.862q-1.665-.006-2.808-.431");
}

.bgxk540zg {
  cx: 18.093px;
  cy: 20.043px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 1.615px;
  ry: 1.849px;
}

.cjn8w2exc {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M36.014 41.011c1.467-3.432 1.368-6.48-.224-9.475q-1.371-2.584-3.744-4.494q2.145-5.432 1.03-8.003q-2.222-5.122-6.507-7.208a6 6 0 0 0-.882-.347l.172-1.154l-1.17.362l-.241-2.54l-4.012 2.307l-.481-1.084q-1.282.102-2.119.929a34.6 34.6 0 0 0-6.322 8.587q-1.908 3.64 1.058 8.44c-3.219-.513-5.141-.264-6.732.78c-.564.368-.374 1.265.189 2.241l7.655 5.707M12.715 41c-1.002-2.224-1.374-4.172-.787-6.251");
}

.ibfbswlrb {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M30.526 14.888c-1.494-.384-2.222.083-2.231 1.389q-.015 2.547 1.86 4.741q.546.64 1.64.371c.75-.184 1.213-1.062 1.223-2.481");
}

.iedaqf9gg {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M16.478 29.054c-1.15-.765-2.55-1.467-3.906-1.724m23.157 4.092c1.732-1.996 3.734-3.727 5.882-5.054q1.992-1.689-.48-2.42c-2.632-.777-5.464-.47-8.297.836M17.035 11.125l-1.273-2.973l-1.123 1.085l-3.802-2.248l-.959 4.232l-2.842-.364l.926 3.24l-1.984.528l5.449 4.438");
}

.rgkf3zbyo {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24.009 21.679c-.209.94.113 2.387.652 3.327m2.496-3.57c-.006 1.189-.04 2.805-.445 3.974");
}

.ujo3lnbds {
  cx: 18.241px;
  cy: 20.179px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 3.404px;
  ry: 3.9px;
}

</style>
