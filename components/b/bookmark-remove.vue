<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u08x6moqp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:bookmark-remove" /></template>
<style>
.u08x6moqp {
  fill: currentColor;
  d: path("M20 7h-5V6h5zM6 19.5V5.616q0-.691.463-1.153T7.616 4h6.153q-.384.596-.577 1.197T13 6.5q0 1.742 1.157 3.012T17 10.958q.287.036.5.036t.5-.036V19.5l-6-2.577z");
}

</style>
