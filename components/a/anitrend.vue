<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="fs9p1bbft"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:anitrend" /></template>
<style>
.fs9p1bbft {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m30.012 42.5l-12.024-37L5.5 42.5m4.162-12.488H25.85M17.988 5.5H42.5m-12.025 37v-37");
}

</style>
