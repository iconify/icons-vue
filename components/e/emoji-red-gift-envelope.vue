<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="onzhp4b1a"/><path class="elp0pim1v"/><path class="pu96x3bse"/><path class="u_1gb0b9p"/><path class="qz3a04t6z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:emoji-red-gift-envelope" /></template>
<style>
.elp0pim1v {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M22.562 19.383a3.1 3.1 0 0 1-1.012-.866v3.446m13.769-8.705a15.1 15.1 0 0 1-5.534 3.97m-11.57 0a15.1 15.1 0 0 1-5.534-3.97m10.944 8.675v-2.937h3.453v2.937m-5.528-6.638v1.464m1.742-1.025h4.104m-3.771 4.486h3.453m-3.453 1.224h3.453m-1.75 0v-2.448");
}

.onzhp4b1a {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M20.38 16.76h2.294a7.17 7.17 0 0 1-2.427 2.973");
}

.pu96x3bse {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M18.043 18.629a5.96 5.96 0 0 0 5.955 5.97a5.963 5.963 0 0 0 5.96-5.965v-.005c0-3.296-2.668-5.968-5.958-5.968s-5.957 2.672-5.957 5.968");
}

.qz3a04t6z {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M12.681 5.5H35.32v37H12.68z");
}

.u_1gb0b9p {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M23.988 16.743h2.674v1.2h-2.674z");
}

</style>
