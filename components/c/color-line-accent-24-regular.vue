<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n9j63_brm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:color-line-accent-24-regular" /></template>
<style>
.n9j63_brm {
  fill: currentColor;
  d: path("M4.004 15.631a2 2 0 0 0 2.571 1.784l4.293-1.288a3.25 3.25 0 0 0 1.159-.627H19.5a1 1 0 0 1 1 1v3a1 1 0 0 1-1 1h-15a1 1 0 0 1-1-1v-3a1 1 0 0 1 .504-.869");
}

</style>
