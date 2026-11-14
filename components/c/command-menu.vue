<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z65v0skzk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:command-menu" /></template>
<style>
.z65v0skzk {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M10.25 7v1.75h3.5V7q0-3.25 3.25-3.25T20.25 7T17 10.25h-1.75v3.5H17q3.25 0 3.25 3.25T17 20.25T13.75 17v-1.75h-3.5V17q0 3.25-3.25 3.25T3.75 17T7 13.75h1.75v-3.5H7q-3.25 0-3.25-3.25T7 3.75T10.25 7m-1.5 0v1.75H7Q5.25 8.75 5.25 7T7 5.25T8.75 7M17 8.75q1.75 0 1.75-1.75T17 5.25T15.25 7v1.75zm-6.75 1.5h3.5v3.5h-3.5zm-3.25 5h1.75V17q0 1.75-1.75 1.75T5.25 17T7 15.25M15.25 17v-1.75H17q1.75 0 1.75 1.75T17 18.75T15.25 17");
}

</style>
