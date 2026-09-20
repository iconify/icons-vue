<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="mkm5vt7zs"/><path class="zlo5lsbvo"/><circle class="hejlv48wp"/><path class="k9ygzpy5e"/><g class="y9tr6bcfx"><path class="uensb_bjo"/><path class="gv2n9o66v"/></g><path class="meqdxgbzy"/><path class="foc7f2z_g"/><path class="cy_-wcw8t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:comici-manga" /></template>
<style>
.cy_-wcw8t {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M39.488 26.022a2.054 2.054 0 0 1-3.961.274l-.43-1.264a2.053 2.053 0 0 1 3.3-2.206");
}

.foc7f2z_g {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M5 35.937c6.079-2.2 9.214-5.773 8.428-10.592C11.45 13.21 21.648 7.225 27.91 7.383c7.821.198 13.175 4.7 14.788 14.124c2.242 13.105-8.504 19.17-13.945 19.112c-5.832-.062-8.94-2.594-12.949-4.068c-3.027-1.113-6.691-1.125-10.803-.614");
}

.gv2n9o66v {
  d: path("M28.438 27.304a2.054 2.054 0 1 1 3.888-1.326l1.093 3.207");
}

.hejlv48wp {
  cx: 38.638px;
  cy: 18.995px;
  r: 0.75px;
  fill: currentColor;
}

.k9ygzpy5e {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m39.45 21.377l1.757 5.151");
}

.meqdxgbzy {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M19.47 30.362a2.054 2.054 0 1 1 3.889-1.326l.43 1.264a2.054 2.054 0 1 1-3.887 1.326zm-.43 2.635a2.054 2.054 0 0 1-3.961.274l-.431-1.264a2.053 2.053 0 0 1 3.3-2.206");
}

.mkm5vt7zs {
  cx: 32.235px;
  cy: 21.18px;
  r: 0.75px;
  fill: currentColor;
}

.uensb_bjo {
  d: path("M24.55 28.63a2.054 2.054 0 1 1 3.888-1.326l1.094 3.207m-5.645-3.825l1.757 5.151");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.zlo5lsbvo {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m33.048 23.561l1.757 5.151");
}

</style>
