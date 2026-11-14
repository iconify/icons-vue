<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="csihkhbxk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:garden-weeder" /></template>
<style>
.csihkhbxk {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("m9.64 13.3l5.189-5.189l1.447-5.308q.02-.072.053-.138t.078-.124t.101-.107t.12-.085t.134-.06t.143-.033q.074-.009.147-.004q.074.005.145.024q.144.04.262.131t.192.221t.093.277t-.02.292l-1.155 4.234l4.234-1.155q.071-.019.145-.024q.073-.005.147.004q.073.009.143.033q.07.023.134.06q.064.036.12.085q.056.048.101.107t.078.124q.033.066.053.138q.039.144.02.292t-.093.277t-.192.221t-.262.131l-5.308 1.447l-1.859 1.859l-3.33 3.33q1.17 1.658-.488 3.316l-3.536 3.536q-1.944 1.944-3.888 0t0-3.888l3.536-3.536Q7.982 12.13 9.64 13.3");
}

</style>
