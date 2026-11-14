<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="onw89m4ia"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:drag-handle" /></template>
<style>
.onw89m4ia {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M9 3.75q-1.75 0-1.75 1.75T9 7.25t1.75-1.75T9 3.75m4.25 1.75q0-1.75 1.75-1.75t1.75 1.75T15 7.25T13.25 5.5M9 10.25q-1.75 0-1.75 1.75T9 13.75T10.75 12T9 10.25M13.25 12q0-1.75 1.75-1.75T16.75 12T15 13.75T13.25 12M9 16.75q-1.75 0-1.75 1.75T9 20.25t1.75-1.75T9 16.75m4.25 1.75q0-1.75 1.75-1.75t1.75 1.75T15 20.25t-1.75-1.75");
}

</style>
