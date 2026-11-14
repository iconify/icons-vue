<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pfgjgqo0t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:hourglass-ancient" /></template>
<style>
.pfgjgqo0t {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M19.067 10.301q-1.981-1.043-4.493-1.384l-1.878-4.696q-.027-.068-.067-.13t-.092-.115t-.113-.094t-.129-.071q-.067-.029-.14-.045q-.072-.015-.146-.016t-.146.013t-.142.041q-.104.041-.191.112q-.088.07-.151.164q-.063.093-.096.2t-.033.22v4.263q-3.642.13-6.317 1.538Q1.75 11.976 1.75 14.5t3.183 4.199Q7.88 20.25 12 20.25t7.067-1.551q3.183-1.675 3.183-4.199t-3.183-4.199M12.9 8.769l-.15-.006v-.369z");
}

</style>
