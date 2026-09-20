<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dq8syh52f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:crop-3-2-sharp" /></template>
<style>
.dq8syh52f {
  fill: currentColor;
  d: path("M4 17V7h16v10z");
}

</style>
