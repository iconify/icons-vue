<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v_r1bgb6x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:game-button-l" /></template>
<style>
.v_r1bgb6x {
  fill: currentColor;
  d: path("M2 20V8q0-1.65 1.175-2.825T6 4h12q1.65 0 2.825 1.175T22 8v12zm8.575-4.475h4.35v-1.3H11.95V8.5h-1.375z");
}

</style>
