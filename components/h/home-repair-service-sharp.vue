<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vyduodyae"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:home-repair-service-sharp" /></template>
<style>
.vyduodyae {
  fill: currentColor;
  d: path("M9 8h6V6H9zM2 20v-5h4v1h2v-1h8v1h2v-1h4v5zm0-6V8h5V4h10v4h5v6h-4v-2h-2v2H8v-2H6v2z");
}

</style>
