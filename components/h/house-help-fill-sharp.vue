<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="obb_b5itp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:house-help-fill-sharp" /></template>
<style>
.obb_b5itp {
  fill: currentColor;
  d: path("M20.659 9.247c.217.19.341.465.341.753v11a1 1 0 0 1-1 1H4a1 1 0 0 1-1-1V10c0-.288.124-.563.341-.753l8-7c.378-.329.94-.329 1.318 0ZM9.236 11.832A3 3 0 0 0 9 13a1 1 0 0 0 2 0a1.001 1.001 0 0 1 1.707-.707a1 1 0 0 1 .215 1.094A.99.99 0 0 1 12 14a1 1 0 0 0 0 2a3 3 0 1 0-2.764-4.168M12.01 17H12a1 1 0 0 0 0 2h.01a1 1 0 0 0 0-2");
}

</style>
