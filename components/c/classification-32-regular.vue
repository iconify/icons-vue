<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="tk6_4tt5a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:classification-32-regular" /></template>
<style>
.tk6_4tt5a {
  fill: currentColor;
  d: path("M25.214 2a4.786 4.786 0 0 1 2.347 8.957l-4.988 2.805l3.114 3.113a4.5 4.5 0 0 1 0 6.364l-4.104 4.104a1.5 1.5 0 0 1-2.122 0l-.726-.727l-2.43 2.43a3.25 3.25 0 0 1-4.595 0l-8.758-8.758a3.25 3.25 0 0 1 0-4.597l2.43-2.43l-.72-.718a1.5 1.5 0 0 1 0-2.121l4.104-4.104a4.5 4.5 0 0 1 6.364 0l3.108 3.108l2.805-4.987A4.79 4.79 0 0 1 25.214 2M4.366 17.106a1.25 1.25 0 0 0 0 1.768l8.758 8.758a1.25 1.25 0 0 0 1.768 0l2.429-2.43L6.795 14.676zm9.35-9.374a2.5 2.5 0 0 0-3.536 0l-3.75 3.75l14.093 14.093l3.75-3.75a2.5 2.5 0 0 0 0-3.536zM25.214 4a2.79 2.79 0 0 0-2.428 1.42l-3.08 5.475l1.399 1.398l5.475-3.08A2.786 2.786 0 0 0 25.214 4");
}

</style>
