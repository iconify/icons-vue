<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="y9tr6bcfx"><path class="jfr1w96jn"/><path class="tfgi2bcvu"/><circle class="ag8ibwknx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:liftoff" /></template>
<style>
.ag8ibwknx {
  cx: 23.769px;
  cy: 19.13px;
  r: 4.137px;
}

.jfr1w96jn {
  d: path("M23.968 43.5c.482 0 4.355-2.488 4.355-6.953h-8.71c0 4.465 3.872 6.953 4.355 6.953m-8.306-23.327c-.717 0-6.474 4.652-6.474 7.29v10.501c1.5-1.5 6.474-4.066 6.474-4.066zm16.676 0c.717 0 6.474 4.652 6.474 7.29v10.501c-1.5-1.5-6.474-4.066-6.474-4.066z");
}

.tfgi2bcvu {
  d: path("M29.943 10.152C28.423 7.912 26.473 5.664 24 4.5c-.924 0-8.338 5.465-8.338 13.312v16.086c5.675 0 10.975.15 16.676 0V17.812");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
