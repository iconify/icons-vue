<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v8vpw56kr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:leaf-growth" /></template>
<style>
.v8vpw56kr {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M11.25 10q0-2.959 2.264-4.884Q15.71 3.25 19 3.25q.074 0 .146.014q.073.015.141.043t.13.069q.061.041.113.094q.053.052.094.113t.069.13t.043.141t.014.146q0 2.959-2.264 4.884q-1.94 1.649-4.736 1.841v6.596q6.359.141 8.344 2.722q.046.058.078.124q.033.067.052.138t.024.145t-.004.147t-.034.143q-.023.07-.06.134t-.086.12q-.048.055-.107.1q-.098.076-.215.116q-.118.04-.242.04h-17q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069t-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141t-.014-.146q0-.124.04-.242t.116-.215q1.985-2.581 8.344-2.722v-1.596q-2.796-.192-4.736-1.841Q4.25 11.959 4.25 9q0-.074.014-.146q.015-.073.043-.141t.069-.13t.094-.113q.052-.053.113-.094t.13-.069t.141-.043T5 8.25q3.29 0 5.486 1.866q.421.358.764.752z");
}

</style>
