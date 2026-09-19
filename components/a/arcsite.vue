<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ewn4p-bau"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:arcsite" /></template>
<style>
.ewn4p-bau {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m24 4.5l15.5 39m-31 0l4.453-11.205c.969-2.328 2.743-3.395 5.572-3.395h15.172");
}

</style>
