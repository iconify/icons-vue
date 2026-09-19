<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="tpf7yjb3e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:appsheet" /></template>
<style>
.tpf7yjb3e {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M30.645 7.718h9.893c1.508 0 2.45 1.632 1.697 2.938L25.697 39.302c-.754 1.307-2.64 1.307-3.393 0l-4.382-7.59a1.96 1.96 0 0 1 0-1.958zH7.462c-1.508 0-2.45 1.632-1.697 2.938l4.382 7.59c.35.606.997.98 1.697.98h25.443");
}

</style>
