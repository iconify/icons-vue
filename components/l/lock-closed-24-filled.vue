<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v5ug5sb1r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:lock-closed-24-filled" /></template>
<style>
.v5ug5sb1r {
  fill: currentColor;
  d: path("M12 1a5 5 0 0 1 5 5v2.01a3.25 3.25 0 0 1 3 3.24v7.5A3.25 3.25 0 0 1 16.75 22h-9.5A3.25 3.25 0 0 1 4 18.75v-7.5a3.25 3.25 0 0 1 3-3.24V6a5 5 0 0 1 5-5m0 12.75a1.25 1.25 0 1 0 0 2.5a1.25 1.25 0 0 0 0-2.5M12 2.5A3.5 3.5 0 0 0 8.5 6v2h7V6A3.5 3.5 0 0 0 12 2.5");
}

</style>
