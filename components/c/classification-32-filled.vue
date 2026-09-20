<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="q8z0e4bbz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:classification-32-filled" /></template>
<style>
.q8z0e4bbz {
  fill: currentColor;
  d: path("M25.214 2a4.787 4.787 0 0 1 2.347 8.957l-4.988 2.805l3.114 3.114a4.5 4.5 0 0 1 0 6.363l-4.104 4.105a1.5 1.5 0 0 1-2.122 0l-.726-.728l-2.429 2.43a3.25 3.25 0 0 1-4.596 0l-8.759-8.758a3.25 3.25 0 0 1 0-4.597l2.43-2.43l-.719-.717a1.5 1.5 0 0 1 0-2.121l4.104-4.105a4.5 4.5 0 0 1 6.364 0l3.108 3.109l2.805-4.988A4.79 4.79 0 0 1 25.214 2M4.366 17.106a1.25 1.25 0 0 0 0 1.768l8.758 8.758a1.25 1.25 0 0 0 1.768 0l2.429-2.43L6.794 14.676zM25.214 4a2.79 2.79 0 0 0-2.428 1.42l-3.08 5.475l1.399 1.399l5.475-3.08A2.786 2.786 0 0 0 25.214 4");
}

</style>
