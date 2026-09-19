<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="deuj91b4n"/><path class="f1c9iuels"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:biltema" /></template>
<style>
.deuj91b4n {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M14.583 15.654h3.361v3.361h-3.361zm6.722 13.444h-3.361v-3.361h3.361v-3.361h-3.361v-3.361h3.361v-3.692h18.221a3.974 3.974 0 1 1 0 7.948h-.73a4.703 4.703 0 0 1 4.704 4.703h0a4.703 4.703 0 0 1-4.703 4.703H21.305zm-6.722-6.722h3.361v3.361h-3.361zm0 6.722h3.361v3.361h-3.361zm-3.361-10.083h3.361v3.361h-3.361zm-3.361-3.361h3.361v3.361H7.861z");
}

.f1c9iuels {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M11.222 25.737h3.361v3.361h-3.361zm-3.361-3.361h3.361v3.361H7.861zm0 6.722h3.361v3.361H7.861zM4.5 19.015h3.361v3.361H4.5zm0 6.722h3.361v3.361H4.5zm23.272-5.613h6.8c.622 0 1.127.504 1.127 1.126h0c0 .621-.505 1.126-1.127 1.126h-6.8zm0 6.35h7.625c.621 0 1.126.505 1.126 1.127h0c0 .621-.505 1.126-1.126 1.126h-7.625z");
}

</style>
