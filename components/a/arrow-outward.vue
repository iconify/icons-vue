<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u2hc5bcan"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:arrow-outward" /></template>
<style>
.u2hc5bcan {
  fill: currentColor;
  d: path("M6.4 18L5 16.6L14.6 7H6V5h12v12h-2V8.4z");
}

</style>
