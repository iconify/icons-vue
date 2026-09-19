<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="h2k5vpb-s"/><path class="v443z_bdn"/><path class="lpfcyqcxc"/><path class="yuyxiacxd"/><path class="oyum0lbwm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:game-center" /></template>
<style>
.h2k5vpb-s {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m31.376 13.781l-2.673-7.658c-1.554-4.454-7.852-4.454-9.406 0l-4.56 13.066c-.922 2.644 1.04 5.408 3.841 5.408H24");
}

.lpfcyqcxc {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m11.676 29.012l-2.34 7.767c-1.361 4.517 3.735 8.219 7.61 5.53l11.369-7.892c2.3-1.597 2.337-4.987.071-6.633L24 24.597");
}

.oyum0lbwm {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m36.566 28.27l6.458-4.908c3.756-2.855 1.81-8.845-2.907-8.947l-13.836-.298c-2.8-.06-4.822 2.66-3.956 5.324L24 24.597");
}

.v443z_bdn {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m15.993 14.24l-8.11.175c-4.716.102-6.663 6.092-2.907 8.946l11.018 8.374c2.23 1.695 5.465.682 6.33-1.982L24 24.597");
}

.yuyxiacxd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m24.39 37.683l6.664 4.625c3.875 2.69 8.971-1.012 7.61-5.53l-3.992-13.25c-.807-2.681-4.02-3.764-6.286-2.118L24 24.597");
}

</style>
