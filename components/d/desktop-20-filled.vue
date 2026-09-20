<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="kel5sp8uc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:desktop-20-filled" /></template>
<style>
.kel5sp8uc {
  fill: currentColor;
  d: path("M3.5 2A1.5 1.5 0 0 0 2 3.5v10A1.5 1.5 0 0 0 3.5 15H7v2H5.5a.5.5 0 0 0 0 1h9a.5.5 0 0 0 0-1H13v-2h3.5a1.5 1.5 0 0 0 1.5-1.5v-10A1.5 1.5 0 0 0 16.5 2zM12 15v2H8v-2z");
}

</style>
