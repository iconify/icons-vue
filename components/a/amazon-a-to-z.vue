<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="cpk0fnbgt"/><path class="qhqaacbnf"/><path class="ojjpw5o-h"/><path class="xfnqi7b2q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:amazon-a-to-z" /></template>
<style>
.cpk0fnbgt {
  cx: 24px;
  cy: 24px;
  r: 21.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.ojjpw5o-h {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M11.798 30.223c1.759 1.397 6.953 3.534 12.488 3.534c3.63.086 7.194-.993 10.167-3.079m-8.597-9.94zc.877 0 1.588.706 1.588 1.577v1.025c0 .87-.71 1.576-1.588 1.576a1.58 1.58 0 0 1-1.587-1.576v-1.025c0-.871.71-1.577 1.587-1.577m-4.466-1.301v4.691a.79.79 0 0 0 .794.788h.238m-1.866-4.178h1.667m9.343-2.622h5.71l-5.71 7.896h5.71m-20.847-2.98c0 1.646-1.268 2.98-2.833 2.98h-.994c-1.037 0-1.877-.884-1.877-1.974s.84-1.974 1.877-1.974h3.832");
}

.qhqaacbnf {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M32.281 29.701c1.112-.451 3.092-1.05 3.687-.327c.645.781-.17 2.477-.92 3.794");
}

.xfnqi7b2q {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M11.438 18.898c.688-.72 1.17-.782 2.498-.782c1.507 0 2.498.692 2.498 2.562v5.334");
}

</style>
