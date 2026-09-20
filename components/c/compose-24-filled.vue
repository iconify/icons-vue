<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a0inccbnp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:compose-24-filled" /></template>
<style>
.a0inccbnp {
  fill: currentColor;
  d: path("M13 4a1 1 0 1 1 0 2H6.5A1.5 1.5 0 0 0 5 7.5v10A1.5 1.5 0 0 0 6.5 19h10a1.5 1.5 0 0 0 1.5-1.5V11a1 1 0 1 1 2 0v6.5a3.5 3.5 0 0 1-3.5 3.5h-10A3.5 3.5 0 0 1 3 17.5v-10A3.5 3.5 0 0 1 6.5 4zm6.293-.707a1 1 0 0 1 1.414 1.414l-9.586 9.586L9 15l.707-2.121z");
}

</style>
