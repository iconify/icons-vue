<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s7_ejyuqc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:home-repair-service-outline-sharp" /></template>
<style>
.s7_ejyuqc {
  fill: currentColor;
  d: path("M2 20V8h5V4h10v4h5v12zm6-5v1H6v-1H4v3h16v-3h-2v1h-2v-1zm-4-5v3h2v-1h2v1h8v-1h2v1h2v-3zm5-2h6V6H9z");
}

</style>
