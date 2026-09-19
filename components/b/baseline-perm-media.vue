<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wgms5w37q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:baseline-perm-media" /></template>
<style>
.wgms5w37q {
  fill: currentColor;
  d: path("M2 6H0v5h.01L0 20c0 1.1.9 2 2 2h18v-2H2zm20-2h-8l-2-2H6c-1.1 0-1.99.9-1.99 2L4 16c0 1.1.9 2 2 2h16c1.1 0 2-.9 2-2V6c0-1.1-.9-2-2-2M7 15l4.5-6l3.5 4.51l2.5-3.01L21 15z");
}

</style>
