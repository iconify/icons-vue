<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="shylf5bgo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:desktop-tower-fill" /></template>
<style>
.shylf5bgo {
  fill: currentColor;
  d: path("M12 6a3 3 0 0 1 3-3h4a3 3 0 0 1 3 3v12a3 3 0 0 1-3 3h-4a3 3 0 0 1-3-3H5a3 3 0 0 1-3-3v-4a3 3 0 0 1 3-3h7Zm5.01 1H17a1 1 0 0 0 0 2h.01a1 1 0 0 0 0-2M12 10H5a.997.997 0 0 0-1 1v4a1 1 0 0 0 1 1h7Zm6 6v-3a1 1 0 0 0-2 0v3a1 1 0 0 0 2 0m-9 3a1 1 0 0 1 0 2H6a1 1 0 0 1 0-2Z");
}

</style>
