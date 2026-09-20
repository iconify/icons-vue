<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g3mme8blc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:garage-door-open-rounded" /></template>
<style>
.g3mme8blc {
  fill: currentColor;
  d: path("M8.327 12.596h7.346v-1.884H8.327zm3.683-4.615q.3 0 .51-.21t.21-.52t-.21-.521t-.52-.21q-.29 0-.51.21q-.22.209-.22.52t.22.52t.52.21M6.615 19.02q-.667 0-1.141-.475T5 17.404v-7.77h-.36q-.282 0-.383-.272t.122-.454l6.638-5.077q.449-.337.983-.337t.983.337l6.638 5.077q.223.18.122.454t-.383.273H19v7.769q0 .666-.475 1.14t-1.14.475h-.904q-.343 0-.576-.232t-.232-.575V13.48H8.327v4.73q0 .344-.232.576t-.576.232z");
}

</style>
