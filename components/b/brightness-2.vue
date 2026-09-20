<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wasmbuevl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:brightness-2" /></template>
<style>
.wasmbuevl {
  fill: currentColor;
  d: path("M9.5 2q2.075 0 3.9.788t3.175 2.137T18.713 8.1T19.5 12t-.788 3.9t-2.137 3.175t-3.175 2.138T9.5 22q-1.325 0-2.588-.337T4.5 20.65Q6.825 19.3 8.163 17T9.5 12T8.162 7T4.5 3.35q1.15-.675 2.413-1.012T9.5 2");
}

</style>
