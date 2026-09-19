<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="rq1-4acyh"/><path class="xqexe0bwe"/><path class="o7z22ccqx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:emoji-palms-up-together" /></template>
<style>
.o7z22ccqx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M27.9 37.93c0-.374-1.239-2.087-1.698-2.087c-.565 0-2.202-.884-2.202-1.978V7.35c.367-1.502 2.602-1.695 2.956.196l1.484 10.065c.259 1.634.989 1.634 1.271 3.267c.389 3.18.76 8.729 4.504 11.001M12.498 14.475l-3.631.148m6.285-2.523l.547-3.593m-2.019 4.64l-1.886-2.105m22.884 3.433l3.63.148M32.024 12.1l-.547-3.593m2.019 4.64l1.885-2.105");
}

.rq1-4acyh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M18.595 41.825H5.5V35.23l8.285-3.352c-1.472 4.825 3.464 7.685 6.315 6.051z");
}

.xqexe0bwe {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M20.1 37.93c0-.374 1.239-2.087 1.698-2.087c.565 0 2.202-.884 2.202-1.978V7.35c-.367-1.502-2.602-1.695-2.956.196l-1.483 10.065c-.26 1.634-.99 1.634-1.272 3.267c-.389 3.18-.76 8.729-4.504 11.001m15.62 9.946H42.5V35.23l-8.285-3.352c1.472 4.825-3.464 7.685-6.315 6.051z");
}

</style>
