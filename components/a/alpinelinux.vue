<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="y9tr6bcfx"><path class="we27h8bls"/><path class="s1m1_5big"/><path class="q80sfmlyb"/><path class="yv-edrbdn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:alpinelinux" /></template>
<style>
.q80sfmlyb {
  d: path("m28.088 22.86l.64-.682l5.041 5.236c1.553 1.085 3.015.436 4.504-.556m-6.65.205L20.718 16.11L9.655 27.048");
}

.s1m1_5big {
  d: path("m25.397 20.402l3.263-3.263l9.613 9.72");
}

.we27h8bls {
  d: path("M14.119 7.227H33.86l9.64 16.696l-9.765 16.913H14.172L4.5 24.084l9.769-16.92");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.yv-edrbdn {
  d: path("m20.69 21.135l5.81 5.833c1.81 2.06 3.38 1.191 5.123.095M20.69 21.135l-5.756 5.682c-1.192 1.255-2.507 2.258-5.279.23m9.572-2.446v4.112c-.571-.068-1.384-.061-2.961-1.148z");
}

</style>
