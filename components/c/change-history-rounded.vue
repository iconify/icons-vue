<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="feo9kyb7d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:change-history-rounded" /></template>
<style>
.feo9kyb7d {
  fill: currentColor;
  d: path("M3.8 20q-.575 0-.875-.513t.025-1.012l8.2-13.125q.3-.475.85-.475t.85.475l8.2 13.125q.325.5.025 1.013T20.2 20z");
}

</style>
