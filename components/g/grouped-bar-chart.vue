<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ji-ln4lds"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:grouped-bar-chart" /></template>
<style>
.ji-ln4lds {
  fill: currentColor;
  d: path("M4 20V8h4v12zm5 0v-7h4v7zm7 0V4h4v16z");
}

</style>
