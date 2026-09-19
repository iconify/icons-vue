<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="adsuezxky"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:kick" /></template>
<style>
.adsuezxky {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M36.75 21.842v-4.25H41V5H28.25v4.25H24v4.25h-4.25V5H7v38h12.75v-8.5H24v4.25h4.25V43H41V30.342h-4.25v-4.25H32.5v-4.25z");
}

</style>
