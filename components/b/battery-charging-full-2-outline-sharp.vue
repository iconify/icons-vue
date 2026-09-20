<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cwsb0xbtz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:battery-charging-full-2-outline-sharp" /></template>
<style>
.cwsb0xbtz {
  fill: currentColor;
  d: path("M2 17V7h14.25l-1.6 2H4v6h11l-.35 2zm14.675 0l.7-4H14l4.8-6h.525l-.7 4H22l-4.8 6zM4 15V9z");
}

</style>
