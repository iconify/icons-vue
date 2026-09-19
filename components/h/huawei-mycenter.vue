<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="k92hkvzfp"/><rect class="v-pmbybdw"/><path class="v8i0x0b1m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:huawei-mycenter" /></template>
<style>
.k92hkvzfp {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m17.822 20.88l-.054 4.772");
}

.v-pmbybdw {
  width: 23.318px;
  height: 10.828px;
  x: 12.421px;
  y: 17.568px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 2.028px;
}

.v8i0x0b1m {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M42.5 24a18.5 18.5 0 1 1-37 0c0-2.554 1.276-8.212 3.17-9.935c0 0-.59-6.827.426-7.596c.862-.652 6.899 1.235 6.899 1.235A14.4 14.4 0 0 1 24 5.5a14.4 14.4 0 0 1 8.404 2.13s5.795-2.1 6.934-1.094s.37 8.028.37 8.028A15.5 15.5 0 0 1 42.5 24m-12.483-3.12l-.054 4.772");
}

</style>
