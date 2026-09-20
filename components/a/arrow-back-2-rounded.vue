<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rzw4xmbkw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:arrow-back-2-rounded" /></template>
<style>
.rzw4xmbkw {
  fill: currentColor;
  d: path("M6.325 12.85q-.225-.15-.337-.375T5.874 12t.113-.475t.337-.375l8.15-5.175q.125-.075.263-.112T15 5.825q.4 0 .7.288t.3.712v10.35q0 .425-.3.713t-.7.287q-.125 0-.262-.038t-.263-.112z");
}

</style>
