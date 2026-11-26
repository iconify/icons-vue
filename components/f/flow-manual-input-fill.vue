<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="a06hoi2op"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:flow-manual-input-fill" /></template>
<style>
.a06hoi2op {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M11.0656 5.7937L18.0656 4.1121C20.5812 3.5077 23 5.4142 23 8.0014L23 16C23 18.2092 21.2092 20 19 20L5 20C2.7908 20 1 18.2092 1 16L1 11.3647C1 9.5154 2.2676 7.9073 4.0656 7.4753Z");
}

</style>
