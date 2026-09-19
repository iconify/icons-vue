<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="gtrqy3bxc"/><path class="t3gzn1b0o"/><path class="jl30vqbgq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:babelio" /></template>
<style>
.gtrqy3bxc {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M7.738 43.5v-6.851a60.17 60.17 0 0 0 32.524-10.014V43.5Z");
}

.jl30vqbgq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M29.346 20.082V4.5s-3.54 9.938-10.842 12.122v9.366");
}

.t3gzn1b0o {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M34.917 29.702V15.279s-11.218 11.52-21.382 11.52v9.536");
}

</style>
