<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t4x-debbd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:android-cell-dual-4-bar-alert-outline-sharp" /></template>
<style>
.t4x-debbd {
  fill: currentColor;
  d: path("M2.866 14.962V9.923h1.692v5.039zm5.519 0V8.616h1.692v6.346zm5.519 0V6.789h1.692v8.173zM2.866 19v-2.577h1.692V19zm5.519 0v-2.577h1.692V19zm5.519 0v-2.577h1.692V19zm5.519-7.46V5h1.693v6.389q-.125-.012-.244-.018t-.256-.006q-.313 0-.619.047q-.306.046-.574.128m.672 7.25q-.21-.21-.21-.52t.21-.521t.52-.21t.52.21t.211.52t-.21.52q-.21.211-.52.211t-.52-.21m.02-2.251v-3.616h1v3.616z");
}

</style>
