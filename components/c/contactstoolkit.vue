<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="cpk0fnbgt"/><path class="a_m2c6btx"/><path class="snlqakb_k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:contactstoolkit" /></template>
<style>
.a_m2c6btx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M15.77 43.728v-8.04c0-2.485 5.237-4.509 11.88-4.509s11.88 2.086 11.88 4.572v3.089M27.789 14.38c5.936-.012 8.918 7.928 4.725 12.577c-4.193 4.65-11.372 1.364-11.372-5.206c0-4.065 2.974-7.363 6.646-7.37zm-25.23 9.687l6.184-7.119M3.422 28.813l7.982-9.672m.872-7.836c-1.56-.184-3.02.362-3.754 1.553c-.723 1.174-.57 2.696.262 3.995m2.893 2.3c1.992.744 4.047.234 4.98-1.28c.523-.847.712-2.482-.007-3.593");
}

.cpk0fnbgt {
  cx: 24px;
  cy: 24px;
  r: 21.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.snlqakb_k {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m12.389 11.363l-1.634 1.995l.842 2.62l3.003.54l1.793-2.104");
}

</style>
