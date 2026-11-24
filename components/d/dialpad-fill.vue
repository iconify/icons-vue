<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eqedirb-h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:dialpad-fill" /></template>
<style>
.eqedirb-h {
  fill: currentColor;
  d: path("M6 3h.01a1 1 0 0 1 0 2H6a1 1 0 0 1 0-2m6 0h.01a1 1 0 0 1 0 2H12a1 1 0 0 1 0-2m6 0h.01a1 1 0 0 1 0 2H18a1 1 0 0 1 0-2M6 8h.01a1 1 0 0 1 0 2H6a1 1 0 0 1 0-2m6 0h.01a1 1 0 0 1 0 2H12a1 1 0 0 1 0-2m6 0h.01a1 1 0 0 1 0 2H18a1 1 0 0 1 0-2M6 13h.01a1 1 0 0 1 0 2H6a1 1 0 0 1 0-2m6 0h.01a1 1 0 0 1 0 2H12a1 1 0 0 1 0-2m6 0h.01a1 1 0 0 1 0 2H18a1 1 0 0 1 0-2m-6 5h.01a1 1 0 0 1 0 2H12a1 1 0 0 1 0-2");
}

</style>
