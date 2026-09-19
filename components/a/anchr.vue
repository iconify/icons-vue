<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="omtat9bkv"/><circle class="t1ifxrbbg"/><path class="k80o1mjqr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:anchr" /></template>
<style>
.k80o1mjqr {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m21.344 23.789l-.072 14.045c-4.271-.972-7.874-2.772-9.793-6.66L14.17 28.5l-9.67.018l.071 9.511l2.87-2.78C11.12 40.62 16.78 42.957 24 42.899m2.763-19.606l-.036 14.54c4.272-.971 7.875-2.771 9.794-6.659L33.83 28.5l9.67.018l-.071 9.511l-2.87-2.78C36.88 40.62 31.22 42.957 24 42.899");
}

.omtat9bkv {
  cx: 23.573px;
  cy: 14.408px;
  r: 9.309px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.t1ifxrbbg {
  cx: 23.573px;
  cy: 14.251px;
  r: 4.515px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
