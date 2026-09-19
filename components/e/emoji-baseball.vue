<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="y99gtib8o"/><path class="h4eg9o1fk"/><circle class="cpk0fnbgt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:emoji-baseball" /></template>
<style>
.cpk0fnbgt {
  cx: 24px;
  cy: 24px;
  r: 21.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.h4eg9o1fk {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m31.38 23.626l1.484.742l1.484-.742m-17.748.742l-1.484-.742l-1.484.742m2.356 5.1l-1.32-1.006l-1.596.452m1.283 5.098l-1.097-1.245l-1.654.13m.225 4.967l-.574-1.557l-1.59-.475m2.663-25.312l-1.595.457l-.592 1.55m4.574 2.258l-1.631.08l-.955 1.377m4.061 3.152l-1.636-.278l-1.203 1.142m18.641-1.733l1.32 1.006l1.596-.452m-1.283-5.097l1.097 1.245l1.654-.13m-.134-5.08l.574 1.557l1.59.475m-2.872 25.27l1.595-.457l.592-1.55m-4.459-2.061l1.657-.082l.929-1.375M31.79 28.6l1.636.278l1.203-1.142");
}

.y99gtib8o {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M39.207 39.253a21.45 21.45 0 0 1-6.343-15.256a21.45 21.45 0 0 1 6.303-15.216m-30.354 0a21.45 21.45 0 0 1 6.303 15.216a21.4 21.4 0 0 1-6.32 15.232");
}

</style>
