<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m1guh_o6n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:edit-sharp" /></template>
<style>
.m1guh_o6n {
  fill: currentColor;
  d: path("M4 20v-2.52l13.875-13.9l2.54 2.563L6.52 20zM17.504 7.589L19 6.111L17.889 5l-1.477 1.496z");
}

</style>
