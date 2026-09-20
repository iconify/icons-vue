<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":26,"height":26};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="bk3_hoper"/><path class="unr03_lwc"/><path clip-rule="evenodd" class="kphejjb8s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons-pop:cart-circle" /></template>
<style>
.bk3_hoper {
  fill-rule: evenodd;
  d: path("M19.513 9h-9.026a2.5 2.5 0 0 0-2.437 3.057l.913 4A2.5 2.5 0 0 0 11.401 18H18.6a2.5 2.5 0 0 0 2.437-1.943l.913-4A2.5 2.5 0 0 0 19.513 9m-9.137 2.013a.5.5 0 0 1 .111-.013h9.026a.5.5 0 0 1 .487.611l-.913 4A.5.5 0 0 1 18.6 16h-7.2a.5.5 0 0 1-.487-.389l-.913-4a.5.5 0 0 1 .376-.598");
}

.cuyn6tgcc {
  fill: currentColor;
}

.kphejjb8s {
  fill-rule: evenodd;
  d: path("M13 24c6.075 0 11-4.925 11-11S19.075 2 13 2S2 6.925 2 13s4.925 11 11 11m0 2c7.18 0 13-5.82 13-13S20.18 0 13 0S0 5.82 0 13s5.82 13 13 13");
}

.unr03_lwc {
  d: path("M6.49 5H5a1 1 0 0 1 0-2h2.29a1 1 0 0 1 .975.78l2.71 12a1 1 0 1 1-1.95.44zM13 20.25a1.75 1.75 0 1 1-3.5 0a1.75 1.75 0 0 1 3.5 0m7 0a1.75 1.75 0 1 1-3.5 0a1.75 1.75 0 0 1 3.5 0");
}

</style>
