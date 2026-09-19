<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="lo88-dbug"/><g class="y9tr6bcfx"><path class="a5_ivtbnz"/><path class="b2gu_rhpg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:bt-scanner" /></template>
<style>
.a5_ivtbnz {
  d: path("m19.585 33.702l19.047-18.937l-9.304-9.29v37.05l9.304-9.29l-19.047-18.937");
}

.b2gu_rhpg {
  d: path("M37.867 20.731c.783.588 1.436 2.09 1.306 3.721c-.131 1.24-.784 2.285-1.306 2.676m2.285-8.942c1.37 1.044 2.48 3.72 2.35 6.658c-.196 2.22-1.306 4.047-2.35 4.83");
}

.lo88-dbug {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M13.768 5.5h-8.28v8.28m37 0V5.5h-8.28m0 37h8.28v-8.28m-31.95-7.81v11h11v-11zm3.22 3.22h4.6v4.6h-4.6zm-3.22-19.08v11h11v-11zm3.22 3.22h4.6v4.6h-4.6zm-8.27 20.45v8.28h8.28");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
