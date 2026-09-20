<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s5b_7ab-y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:battery-charging-full-outline-sharp" /></template>
<style>
.s5b_7ab-y {
  fill: currentColor;
  d: path("M16.5 22v-3H14l3.5-5v3H20zM7 22V4h3V2h4v2h3v8q-.525 0-1.025.088T15 12.35V6H9v14h2.35q.2.575.488 1.075t.687.925z");
}

</style>
