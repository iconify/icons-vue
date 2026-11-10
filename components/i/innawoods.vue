<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="eqh_3kbrt"/><path class="rlbywnb_i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:innawoods" /></template>
<style>
.eqh_3kbrt {
  cx: 24px;
  cy: 24px;
  r: 21.5px;
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
}

.rlbywnb_i {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  d: path("M22.368 20.691h3.264v3.264h-3.264zm9.212 23.396V30.488l7.712-7.713L37 20.483l-8.801 8.8v5.557l-2.37-2.37v-6.528h-1.826m-7.578 18.146v-13.6l-7.712-7.712l2.292-2.292l8.8 8.8v5.557l2.371-2.37v-6.528h1.826");
}

</style>
