<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qnmzx0slh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:battery-charging-full-2-outline" /></template>
<style>
.qnmzx0slh {
  fill: currentColor;
  d: path("M3 17q-.425 0-.712-.288T2 16V8q0-.425.288-.712T3 7h13.25l-1.6 2H4v6h11l-.35 2zm13.675 0l.7-4H14l4.8-6h.525l-.7 4H22l-4.8 6zM4 15V9z");
}

</style>
