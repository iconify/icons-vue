<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="y9tr6bcfx"><path class="hau6sxb8r"/><path class="jfqbjtbpk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:caf" /></template>
<style>
.hau6sxb8r {
  d: path("M30.094 11.132c-.697 2.958-3.544 5.235-6.359 5.086s-4.531-2.667-3.834-5.625s3.544-5.235 6.359-5.086s4.531 2.667 3.834 5.625");
}

.jfqbjtbpk {
  d: path("m31.138 26.774l8.762-5.066c5.602-2.8 1.32-11.254-4.984-8.103l-11.34 6.572l-9.518-6.354c-6.743-3.858-11.909 5.432-5.917 8.86l6.24 4.091l-1.6 11.718c3.831 4.265 11.057 5.291 16.445 2.275z");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
