<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="io0k3absg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:clipboard-month-24-filled" /></template>
<style>
.io0k3absg {
  fill: currentColor;
  d: path("M13.75 2h-3.5a2.25 2.25 0 0 0-2.236 2H6.25A2.25 2.25 0 0 0 4 6.25v13.5A2.25 2.25 0 0 0 6.25 22h11.5A2.25 2.25 0 0 0 20 19.75V6.25A2.25 2.25 0 0 0 17.75 4h-1.764a2.25 2.25 0 0 0-2.236-2m-3.5 1.5h3.5a.75.75 0 0 1 0 1.5h-3.5a.75.75 0 0 1 0-1.5m-2 9a1.25 1.25 0 1 1 0-2.5a1.25 1.25 0 0 1 0 2.5m0 4a1.25 1.25 0 1 1 0-2.5a1.25 1.25 0 0 1 0 2.5m9.25-5.25a1.25 1.25 0 1 1-2.5 0a1.25 1.25 0 0 1 2.5 0m-5.25 1.25a1.25 1.25 0 1 1 0-2.5a1.25 1.25 0 0 1 0 2.5m1.25 2.75a1.25 1.25 0 1 1-2.5 0a1.25 1.25 0 0 1 2.5 0");
}

</style>
