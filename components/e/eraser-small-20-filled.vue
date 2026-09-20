<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="jt0byc3eq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:eraser-small-20-filled" /></template>
<style>
.jt0byc3eq {
  fill: currentColor;
  d: path("M2.44 11.2a1.5 1.5 0 0 0 0 2.122l4.242 4.242a1.5 1.5 0 0 0 2.121 0l2.212-2.212a4 4 0 0 1 4.337-4.337l2.212-2.212a1.5 1.5 0 0 0 0-2.121l-4.242-4.243a1.5 1.5 0 0 0-2.122 0zm.706 1.415a.5.5 0 0 1 0-.707l1.69-1.69l4.95 4.95l-1.69 1.69a.5.5 0 0 1-.707 0zM15 18a3 3 0 1 0 0-6a3 3 0 0 0 0 6");
}

</style>
