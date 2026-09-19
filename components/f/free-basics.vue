<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="f2fnqnb7q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:free-basics" /></template>
<style>
.f2fnqnb7q {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M14.762 36.582c-2.992-2.64-4.84-6.423-4.84-10.646c0-5.455 3.168-10.206 7.743-12.582m7.567-1.408a14.005 14.005 0 0 1 12.845 13.99c0 7.742-6.334 14.077-14.077 14.077c-1.32 0-2.64-.176-3.871-.528M11.331 44.5l17.508-41");
}

</style>
