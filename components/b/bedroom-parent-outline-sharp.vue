<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wdsccr4ak"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:bedroom-parent-outline-sharp" /></template>
<style>
.wdsccr4ak {
  fill: currentColor;
  d: path("M5 17h1.5v-1.5h11V17H19v-6.5h-.75V7H5.75v3.5H5zm7.75-6.5v-2h4v2zm-5.5 0v-2h4v2zM6.5 14v-2h11v2zM2 22V2h20v20zm2-2h16V4H4zm0 0V4z");
}

</style>
