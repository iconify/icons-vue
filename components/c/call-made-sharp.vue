<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qb164absy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:call-made-sharp" /></template>
<style>
.qb164absy {
  fill: currentColor;
  d: path("M5.4 20L4 18.6L15.6 7H9V5h10v10h-2V8.4z");
}

</style>
