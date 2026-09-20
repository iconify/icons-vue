<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="uvixfrc4b"/><path class="kqfung82n"/><path class="fch2lx2zl"/><path class="on2_kdbgd"/><path class="b8zx7wbdi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:clicker-for-whatsapp" /></template>
<style>
.b8zx7wbdi {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m27.15 29.483l1.473-1.473a1.944 1.944 0 0 1 2.749 2.749l-2.821 2.82c-1.86 1.86-4.5 2.937-6.548 4.986l-9.944-9.944c2.371-2.156 2.87-6.97 3.234-9.648c.206-1.518.943-1.913 2.344-1.698s1.617 2.372 1.078 4.15");
}

.fch2lx2zl {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m21.653 23.985l3.503-3.503a1.944 1.944 0 0 1 2.749 2.749L24.4 26.734");
}

.kqfung82n {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m17.556 22.584l10.58-10.58a1.944 1.944 0 0 1 2.749 2.749l-9.233 9.233");
}

.on2_kdbgd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m24.401 26.734l2.533-2.533a1.944 1.944 0 0 1 2.749 2.749l-2.533 2.533");
}

.uvixfrc4b {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 2.502c-11.884.013-21.508 9.657-21.495 21.541A21.5 21.5 0 0 0 5.152 34.36l-1.65 10.139l10.139-1.65c10.41 5.71 23.477 1.901 29.188-8.509s1.9-23.477-8.509-29.187A21.5 21.5 0 0 0 24 2.502");
}

</style>
