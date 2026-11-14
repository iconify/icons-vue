<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u6vxjqwte"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:garden-scissors" /></template>
<style>
.u6vxjqwte {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M9.836 15.961q.914.937.914 2.789q0 3.75-3.75 3.75t-3.75-3.75T7 15q.871 0 1.539.202l2.565-3.917l-5.482-8.374q-.04-.062-.068-.131q-.027-.068-.041-.141T5.5 2.493t.016-.146t.044-.141t.07-.129t.095-.112q.052-.052.114-.093q.062-.04.131-.068q.068-.027.141-.041t.146-.013q.074.001.146.016q.073.015.141.044t.129.07q.061.042.112.095q.052.052.093.114L12 9.915l5.122-7.826q.082-.125.205-.209q.124-.084.27-.114q.146-.031.292-.003q.147.028.272.109q.062.041.114.093q.053.051.095.112q.041.061.07.129t.044.141t.016.146t-.013.146t-.041.141t-.068.131l-5.482 8.374l2.565 3.917Q16.129 15 17 15q3.75 0 3.75 3.75T17 22.5t-3.75-3.75q0-1.852.914-2.789L12 12.654z");
}

</style>
