<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="z-mt63bok"/><path class="me5rg9bjg"/><path class="nr9j6jb5z"/><path class="xom4xmi2j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:http-injector" /></template>
<style>
.me5rg9bjg {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M19.447 26.005v2.977c0 .63.507 1.136 1.137 1.136h6.832c.63 0 1.137-.507 1.137-1.136V25.55l3.516 3.296M19.448 19.3l-3.517 3.296v6.25l3.516-3.296m12.622-2.954v6.25m-12.622-2.841v-6.25");
}

.nr9j6jb5z {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M19.447 19.755V15.56c0-.63.507-1.137 1.137-1.137h6.832c.63 0 1.137.507 1.137 1.137v4.196m0 6.25V19.3l3.516 3.296");
}

.xom4xmi2j {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M19.447 26.005v2.977c0 .63.507 1.136 1.137 1.136h6.832c.63 0 1.137-.507 1.137-1.136V25.55l3.516 3.296M19.448 19.3l-3.517 3.296v6.25l3.516-3.296m1.651-11.127V13.16c0-.63.507-1.136 1.137-1.136m1.765 0h1.765m0 0c.63 0 1.137.507 1.137 1.136v1.265m-4.667-2.401H24V4.5");
}

.z-mt63bok {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M21.877 34.305c-1.158.854-.898 2.763-.84 4.522l1.317-1.641c-.613 2.475.289 4.9 1.646 6.314c1.357-1.415 2.259-3.84 1.646-6.314l1.316 1.641c.06-1.76.32-3.668-.84-4.522m2.627 0h-9.498m7.111-4.186v4.186m-4.725 0v-4.186m10.432-7.522v6.25m-12.622-2.841v-6.25m0 0V15.56c0-.63.507-1.137 1.137-1.137h6.832c.63 0 1.137.507 1.137 1.137v4.196m0 6.25V19.3l3.516 3.296");
}

</style>
