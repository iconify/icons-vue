<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="zwuroqbyh"/><path class="dv_r6zbgv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:drama-player" /></template>
<style>
.dv_r6zbgv {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M17.547 38.001L32.68 27.406a4.156 4.156 0 0 0 0-6.81L17.547 10.003v21");
}

.zwuroqbyh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M43.156 14.24c4.721 9.265 2.135 20.581-6.143 26.875s-19.872 5.763-27.539-1.263C1.808 32.829.268 21.322 5.816 12.53C11.365 3.734 22.412.172 32.053 4.067m4.885 2.763c1.1.83 2.117 1.762 3.039 2.785");
}

</style>
