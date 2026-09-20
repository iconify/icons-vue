<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="x-g6s_oci"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:evidea" /></template>
<style>
.x-g6s_oci {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M42.5 22.216h-37L24 5.77zm-4.523 12.569l-27.275-9.977c-.937-.342-1.806.809-1.806 1.806v13.81c0 .997.808 1.806 1.806 1.806h27.275c.998 0 1.807-.809 1.807-1.806V36.59c0-.997-.87-1.463-1.807-1.806M42.5 22.216l-9.87 10.613m-21.928-8.021l4.537-2.592");
}

</style>
