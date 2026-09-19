<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="v-hz52bxy"/><circle class="eziwajb_z"/><circle transform="rotate(-89.912 33.955 42.838)" class="pc9zi4qjd"/><circle class="h862tsn1z"/><path class="x9b2julpk"/><circle class="kzm_8tf9k"/><path class="ssfxa11pq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:family-space" /></template>
<style>
.eziwajb_z {
  cx: 10.943px;
  cy: 6.795px;
  r: 2.662px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.h862tsn1z {
  cx: 36.388px;
  cy: 16.223px;
  r: 2.662px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.kzm_8tf9k {
  cx: 24.089px;
  cy: 20.774px;
  r: 2.51px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.pc9zi4qjd {
  cx: 33.955px;
  cy: 42.839px;
  r: 2.662px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.ssfxa11pq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M18.41 30.386c-1.002.047-1.11-.393-1.143-.874v-1.983c2.804-3.289 11.062-2.874 13.266.067v1.647c-.09.383-.051.844-.562.975z");
}

.v-hz52bxy {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M16.265 3.957a21.294 21.294 0 0 1 25.623 8.288a21.29 21.29 0 0 1-2.99 26.762m-10.945 5.71A21.294 21.294 0 0 1 6.557 11.582");
}

.x9b2julpk {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.919 21.426a15.21 15.21 0 0 1-9.674 16.644a15.21 15.21 0 1 1 3.38-26.697");
}

</style>
