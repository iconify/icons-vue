<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="skfqn5bko"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:arrow-autofit-height-in-20-filled" /></template>
<style>
.skfqn5bko {
  fill: currentColor;
  d: path("m14.78 7.78l2-2a.75.75 0 0 0-1.06-1.06l-.72.72V2.75a.75.75 0 0 0-1.5 0v2.69l-.72-.72a.75.75 0 1 0-1.06 1.06l2 2a.75.75 0 0 0 1.06 0M3 5a2 2 0 0 1 2-2h4.25a.75.75 0 0 1 0 1.5H5a.5.5 0 0 0-.5.5v10a.5.5 0 0 0 .5.5h4.25a.75.75 0 0 1 0 1.5H5a2 2 0 0 1-2-2zm13.78 9.22l-2-2a.75.75 0 0 0-1.06 0l-2 2a.75.75 0 1 0 1.06 1.06l.72-.72v2.69a.75.75 0 0 0 1.5 0v-2.69l.72.72a.75.75 0 1 0 1.06-1.06");
}

</style>
