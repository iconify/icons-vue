<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fm2npimwz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:baseline-cottage" /></template>
<style>
.fm2npimwz {
  fill: currentColor;
  d: path("M12 3L6 7.58V6H4v3.11L1 11.4l1.21 1.59L4 11.62V21h7v-6h2v6h7v-9.38l1.79 1.36L23 11.4zm-2-2c0 1.66-1.34 3-3 3c-.55 0-1 .45-1 1H4c0-1.66 1.34-3 3-3c.55 0 1-.45 1-1z");
}

</style>
