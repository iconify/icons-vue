<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="szqv9tq5a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:logitech-g" /></template>
<style>
.szqv9tq5a {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M25.36 20.372v8.163h9.524v9.523h8.162V20.372zM24.453 4.5a19.5 19.5 0 0 0 0 39v-9.07a10.43 10.43 0 0 1 0-20.86z");
}

</style>
