<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ore2owbiv"/><path class="ferhs5bnk"/><path class="cj0m4tb0i"/><path class="or7qnzjax"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:emoji-bird" /></template>
<style>
.cj0m4tb0i {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M4.5 32.61s19.21-17.665 25.389-16.893S31.433 25.95 25.64 29.33S4.5 32.61 4.5 32.61");
}

.ferhs5bnk {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M27.784 15.971s-.812-11.566 9.055-5.66c0 0 6.371.58 6.661 2.607c0 0-5.889 1.255-7.433 4.344s2.317 5.406-3.958 12.067c0 0-2.993 3.378-7.626 3.378l-.773 1.545l1.545 3.861l4.634.773");
}

.or7qnzjax {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24.483 32.452c-2.67-.209-5.323-1.296-5.323-1.296");
}

.ore2owbiv {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m21.876 39.368l3.379-1.255m-4.151-10.136s6.468-1.448 8.785-9.17");
}

</style>
