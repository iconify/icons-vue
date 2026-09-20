<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ezhzhsp4e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:battery-android-alert-rounded" /></template>
<style>
.ezhzhsp4e {
  fill: currentColor;
  d: path("M4.385 17q-.994 0-1.69-.695T2 14.615v-5.23q0-.994.696-1.69T4.385 7h12.961q.31 0 .54.23t.23.54v7.846q0 .142.009.273t.046.273q.068.327-.093.582t-.465.256zm16.095-.98q-.21-.209-.21-.52t.21-.52q.209-.21.52-.21t.52.21q.21.209.21.52t-.21.52q-.209.21-.52.21t-.52-.21m.163-3.048q-.143-.144-.143-.356V8q0-.213.144-.356t.357-.144t.356.144T21.5 8v4.616q0 .212-.144.356t-.357.144t-.356-.144");
}

</style>
