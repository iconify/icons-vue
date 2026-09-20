<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="c-r52ubsi"/><path class="rx756yhul"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:flag-for-england" /></template>
<style>
.c-r52ubsi {
  fill: var(--svg-color--eee, #eee);
  d: path("M32 5H4a4 4 0 0 0-4 4v18a4 4 0 0 0 4 4h28a4 4 0 0 0 4-4V9a4 4 0 0 0-4-4");
}

.rx756yhul {
  fill: var(--svg-color--ce1124, #ce1124);
  d: path("M21 5h-6v10H0v6h15v10h6V21h15v-6H21z");
}

</style>
