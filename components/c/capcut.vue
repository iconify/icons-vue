<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="d1kyr4b8c"/><path class="v1ac39bgt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:capcut" /></template>
<style>
.d1kyr4b8c {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M43.5 35.9L4.505 16.242v-1.383a3.717 3.717 0 0 1 3.722-3.728h21.998a3.717 3.717 0 0 1 3.722 3.728v1.695");
}

.v1ac39bgt {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m43.5 11.836l-39 19.66l.005 1.645a3.717 3.717 0 0 0 3.723 3.728h21.996a3.717 3.717 0 0 0 3.723-3.728v-1.948");
}

</style>
