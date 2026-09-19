<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="rxhn-ez-p"/><path class="pbxx3mb5n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:cepsa" /></template>
<style>
.pbxx3mb5n {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M43 37.751V25.878c0-9.119-7.392-16.51-16.51-16.51H12.822v7.054l22.634.016l.093 21.248z");
}

.rxhn-ez-p {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m5 19.122l7.82 2.818l-.106 13.914l-7.573 2.748zm15.112.03l7.82 2.818l-.105 13.915l-7.574 2.748z");
}

</style>
