<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lw6vdcc3z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:border-outer-fill-round" /></template>
<style>
.lw6vdcc3z {
  fill: currentColor;
  d: path("M2 7a5 5 0 0 1 5-5h10a5 5 0 0 1 5 5v10a5 5 0 0 1-1.464 3.536A5 5 0 0 1 17 22H7a5 5 0 0 1-5-5Zm10.01-1H12a1 1 0 0 0 0 2h.01a1 1 0 0 0 0-2m-5 5H7a1 1 0 0 0 0 2h.01a1 1 0 0 0 0-2M12 11a1 1 0 0 0 0 2h.01a1 1 0 0 0 0-2Zm5.01 0H17a1 1 0 0 0 0 2h.01a1 1 0 0 0 0-2M12 16a1 1 0 0 0 0 2h.01a1 1 0 0 0 0-2Z");
}

</style>
