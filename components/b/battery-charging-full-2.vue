<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ul9zfhbet"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:battery-charging-full-2" /></template>
<style>
.ul9zfhbet {
  fill: currentColor;
  d: path("M3 17q-.425 0-.712-.288T2 16V8q0-.425.288-.712T3 7h13.25L12 12.3V15h3l-.35 2zm13.675 0l.7-4H14l4.8-6h.525l-.7 4H22l-4.8 6z");
}

</style>
