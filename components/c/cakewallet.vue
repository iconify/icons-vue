<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="r86l76blg"/><path class="lty5zfb3q"/><path class="s5k8dohxt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:cakewallet" /></template>
<style>
.lty5zfb3q {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m22.49 33.316l5.314-5.313c1.987-1.985 2.976.493 4.402-.895c1.264-1.23.413-3.918 2.588-6.093l3.022-3.02");
}

.r86l76blg {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M10.462 32.301c-.592-.593-.636-.81-.636-1.587V12.801c0-1.176.91-2.061 2.179-2.333l24.166-5.173c1.256-.27 1.803.589.734 1.678L22.99 21.17c-.518.528-.629.705-.629 1.872v18.599c0 .854-1.059 1.513-1.77.8zm12.028-4.776l15.326-15.32");
}

.s5k8dohxt {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M20.71 42.547c.588.554 1.556.221 1.993-.215l14.083-14.025c.605-.602 1.388-1.346 1.388-2.343V6.313c.016-1.372-1.238-1.224-2.003-1.019");
}

</style>
