<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ukhs95b4r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:battery-charging-90" /></template>
<style>
.ukhs95b4r {
  fill: currentColor;
  d: path("M8 22q-.425 0-.712-.288T7 21V5q0-.425.288-.712T8 4h2V2h4v2h2q.425 0 .713.288T17 5v7q-2.5.025-4.25 1.763T11 18q0 1.15.4 2.175T12.525 22zM9 8h6V6H9zm7.5 14v-3H14l3.5-5v3H20z");
}

</style>
