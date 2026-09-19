<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="mkm5vt7zs"/><path class="zlo5lsbvo"/><circle class="hejlv48wp"/><path class="l67gixbws"/><path class="foc7f2z_g"/><path class="d0kx6zxqd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:comici-manga" /></template>
<style>
.d0kx6zxqd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M39.488 26.022a2.05 2.05 0 0 1-1.354 1.555h0a2.054 2.054 0 0 1-2.607-1.281l-.43-1.264a2.054 2.054 0 0 1 1.28-2.607h0a2.05 2.05 0 0 1 2.019.4");
}

.foc7f2z_g {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M5 35.937c6.079-2.2 9.214-5.773 8.428-10.592C11.45 13.21 21.648 7.225 27.91 7.383c7.821.198 13.175 4.7 14.788 14.124c2.242 13.105-8.504 19.17-13.945 19.112c-5.832-.062-8.94-2.594-12.949-4.068c-3.027-1.113-6.691-1.125-10.803-.614");
}

.hejlv48wp {
  cx: 38.638px;
  cy: 18.995px;
  r: 0.75px;
  fill: currentColor;
}

.l67gixbws {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m39.45 21.377l1.757 5.151M24.55 28.63a2.054 2.054 0 0 1 1.28-2.607h0a2.054 2.054 0 0 1 2.607 1.28l1.094 3.208m-5.644-3.825l1.757 5.151m2.794-4.533a2.054 2.054 0 0 1 1.28-2.607h0a2.054 2.054 0 0 1 2.607 1.28l1.094 3.208M19.47 30.362a2.054 2.054 0 1 1 3.889-1.326l.43 1.264a2.054 2.054 0 1 1-3.887 1.326zm-.43 2.635a2.05 2.05 0 0 1-1.354 1.555h0a2.054 2.054 0 0 1-2.607-1.281l-.431-1.264a2.054 2.054 0 0 1 1.28-2.607h0a2.05 2.05 0 0 1 2.02.4");
}

.mkm5vt7zs {
  cx: 32.235px;
  cy: 21.18px;
  r: 0.75px;
  fill: currentColor;
}

.zlo5lsbvo {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m33.048 23.561l1.757 5.151");
}

</style>
