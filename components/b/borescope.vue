<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s8v8812bt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:borescope" /></template>
<style>
.s8v8812bt {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M4.75 7.75q-3 0-3-3t3-3t3 3q0 .97-.313 1.626l3.847 3.847Q13.087 8.75 15.5 8.75q2.796 0 4.773 1.977T22.25 15.5t-1.977 4.773T15.5 22.25t-4.773-1.977T8.75 15.5q0-2.413 1.473-4.216L6.376 7.437q-.656.313-1.626.313");
}

</style>
