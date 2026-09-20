<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="rls_ixb8l"/><path class="r0bgriydj"/><path class="zgqbobhet"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:canaveral-900" /></template>
<style>
.r0bgriydj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24.058 16.409c4.92 0 8.913 3.993 8.913 8.92a8.91 8.91 0 0 1-8.91 8.914h-.003c-4.927 0-8.92-3.987-8.92-8.914s3.993-8.92 8.92-8.92");
}

.rls_ixb8l {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m5.5 36.801l37-4.117m-28.08 2.969c-5.704-5.321-6.015-14.26-.694-19.964c5.321-5.705 14.26-6.015 19.964-.694a14.125 14.125 0 0 1 2.126 18.152");
}

.zgqbobhet {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24.104 21.49a3.901 3.901 0 0 1 .004 7.802h-.004a3.9 3.9 0 0 1-3.893-3.901a3.9 3.9 0 0 1 3.894-3.901z");
}

</style>
