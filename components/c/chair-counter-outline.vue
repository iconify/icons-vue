<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p3mk4bhem"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:chair-counter-outline" /></template>
<style>
.p3mk4bhem {
  fill: currentColor;
  d: path("M9.85 7h4.3l.35-1H18q0-.825-.587-1.412T16 4H8q-.825 0-1.412.588T6 6h3.5zM7 22v-1.5q.9-.625 1.913-.975T11 19.05V17H8v-2h3V9H9.5q-.5 0-.875-.288T8.1 8H6q-.8 0-1.4-.537T4 6.125Q4 4.4 5.15 3.2T8 2h8q1.7 0 2.85 1.2T20 6.125q0 .8-.6 1.338T18 8h-2.1q-.15.425-.525.713T14.5 9H13v6h3v2h-3v2.05q1.075.125 2.088.475T17 20.5V22zM9.85 7h4.3z");
}

</style>
