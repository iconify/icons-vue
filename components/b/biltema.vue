<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="arxfdgc2x"/><path class="cbwd662ej"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:biltema" /></template>
<style>
.arxfdgc2x {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M14.583 15.654h3.361v3.361h-3.361zm6.722 13.444h-3.361v-3.361h3.361v-3.361h-3.361v-3.361h3.361v-3.692h18.221a3.974 3.974 0 1 1 0 7.948h-.73a4.703 4.703 0 0 1 0 9.406h-17.49zm-6.722-6.722h3.361v3.361h-3.361zm0 6.722h3.361v3.361h-3.361zm-3.361-10.083h3.361v3.361h-3.361zm-3.361-3.361h3.361v3.361H7.861z");
}

.cbwd662ej {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M11.222 25.737h3.361v3.361h-3.361zm-3.361-3.361h3.361v3.361H7.861zm0 6.722h3.361v3.361H7.861zM4.5 19.015h3.361v3.361H4.5zm0 6.722h3.361v3.361H4.5zm23.272-5.613h6.8a1.127 1.127 0 0 1 0 2.252h-6.8zm0 6.35h7.625a1.127 1.127 0 0 1 0 2.252h-7.625z");
}

</style>
