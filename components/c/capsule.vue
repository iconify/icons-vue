<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="udaxjm76f"/><path class="ba7fe8dvh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:capsule" /></template>
<style>
.ba7fe8dvh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M18.818 18.818h-8.124C7.824 18.818 5.5 21.143 5.5 24s2.325 5.182 5.194 5.182h8.124l10.364-10.364h8.124c2.87 0 5.194 2.325 5.194 5.182s-2.325 5.182-5.194 5.182h-8.124");
}

.udaxjm76f {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M29.183 10.688a5.183 5.183 0 0 0-10.366 0v26.624a5.183 5.183 0 0 0 10.366 0z");
}

</style>
