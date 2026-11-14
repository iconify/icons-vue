<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="knh6-pbwp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:face-buttons" /></template>
<style>
.knh6-pbwp {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M12 1.75q-3.75 0-3.75 3.75T12 9.25t3.75-3.75T12 1.75m-6.5 6.5q-3.75 0-3.75 3.75t3.75 3.75T9.25 12T5.5 8.25M14.75 12q0-3.75 3.75-3.75T22.25 12t-3.75 3.75T14.75 12m-6.5 6.5q0-3.75 3.75-3.75t3.75 3.75T12 22.25T8.25 18.5");
}

</style>
