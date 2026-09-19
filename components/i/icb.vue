<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="tk7kytzbz"/><path class="cblq-tbsn"/><path class="epe57obhj"/><path class="ljz8_xb-p"/><path class="ri6y_4lft"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:icb" /></template>
<style>
.cblq-tbsn {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M33.471 31.448c4.145-1.883 8.294-5.406 8.294-10.556c0-2.444-4.201-5.457-8.473-1.048");
}

.epe57obhj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M33.141 28.475c3.692-1.342 4.387-2.782 4.387-5.008s-3.528-1.13-4.49-.26m-6.527-5.08c-.58 7.86.152 17.342.152 17.342M11.27 20.36c.47 4.58.29 9.09-.8 14.41c-2.31 1.14-2.18 5.02-.48 6.42c1.7 1.39 8.69 1.31 12.27 1.31");
}

.ljz8_xb-p {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M18.096 19.627c.394 7.513-.25 15.846-.25 15.846");
}

.ri6y_4lft {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M22.503 5.5c4.416.04 4.365 2.052 7.463 2.4s5.063.612 5.98 3.754s1.847 3.928.93 4.292s-2.396-3.608-3.838-2.546s-.454 4.561-3.16 4.194s-5.309-3.321-7.39-2.885s-2.094 5.514-4.815 4.86s-.305-5.689-4.51-5.413s-.19 6.414-2.778 7.333c-1.46.518-3.768-.8-4.132-6.809s5.005-8.83 7.172-8.889s3.433.931 5.5.611s1.949-.916 3.578-.902");
}

.tk7kytzbz {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M34.302 13.647c-1.484 7.158-1.866 13.268-.25 21.124c2.3 1.135 2.17 5.02.468 6.416s-8.683 1.309-12.263 1.309");
}

</style>
