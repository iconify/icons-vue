<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="za2sy3kpo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:battery-charging-50-outline-sharp" /></template>
<style>
.za2sy3kpo {
  fill: currentColor;
  d: path("M16.5 22v-3H14l3.5-5v3H20zM7 22V4h3V2h4v2h3v8q-.525 0-1.025.088T15 12.35V6H9v8h3.55q-.725.8-1.137 1.813T11 18q0 1.15.4 2.175T12.525 22z");
}

</style>
