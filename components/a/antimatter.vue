<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ubufuhlui"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:antimatter" /></template>
<style>
.ubufuhlui {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M3.141 8.641Q1.75 10.032 1.75 12t1.391 3.359T6.5 16.75t3.359-1.391T11.25 12T9.859 8.641T6.5 7.25T3.141 8.641M12.75 12q0-1.968 1.391-3.359T17.5 7.25t3.359 1.391T22.25 12t-1.391 3.359T17.5 16.75t-3.359-1.391T12.75 12");
}

</style>
