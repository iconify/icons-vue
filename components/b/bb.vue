<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><path id="SVGKjS48d6i" class="cbqh7xb0b"/></defs><use href="#SVGKjS48d6i" class="c-zrgpb5l"/><use href="#SVGKjS48d6i" class="c-zrgpb5l"/><path class="rmcb9cc9x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:bb" /></template>
<style>
.c-zrgpb5l {
  stroke-linecap: round;
  stroke-linejoin: round;
}

.cbqh7xb0b {
  fill: none;
  stroke: currentColor;
  d: path("M29.48 16.98L9.261 30.643l15.592 10.551L41.4 30.012m-4.369-2.956l4.369 2.956m-11.603 1.933l7.234-4.889M5.5 40.372l4.85-3.278m19.447-5.149l4.369 2.956");
}

.rmcb9cc9x {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m18.52 31.02l20.219-13.663L23.147 6.806L6.6 17.988m4.369 2.956L6.6 17.988m11.603-1.933l-7.234 4.889M42.5 7.628l-4.85 3.278m-19.447 5.149l-4.369-2.956");
}

</style>
