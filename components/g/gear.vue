<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="u0e9kh2sd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:gear" /></template>
<style>
.u0e9kh2sd {
  fill: var(--svg-color--66757f, #66757f);
  d: path("M34 15h-3.362a12.9 12.9 0 0 0-1.582-3.814l2.379-2.379a2 2 0 0 0 0-2.829l-1.414-1.414a2 2 0 0 0-2.828 0l-2.379 2.379A13 13 0 0 0 21 5.362V2a2 2 0 0 0-2-2h-2a2 2 0 0 0-2 2v3.362a12.9 12.9 0 0 0-3.814 1.582L8.808 4.565a2 2 0 0 0-2.828 0L4.565 5.979a2 2 0 0 0-.001 2.829l2.379 2.379A12.9 12.9 0 0 0 5.362 15H2a2 2 0 0 0-2 2v2a2 2 0 0 0 2 2h3.362a12.9 12.9 0 0 0 1.582 3.813l-2.379 2.379c-.78.78-.78 2.048.001 2.829l1.414 1.414c.78.78 2.047.78 2.828 0l2.379-2.379a12.9 12.9 0 0 0 3.814 1.582V34a2 2 0 0 0 2 2h2a2 2 0 0 0 2-2v-3.362a12.9 12.9 0 0 0 3.813-1.582l2.379 2.379a2 2 0 0 0 2.828 0l1.414-1.414a2 2 0 0 0 0-2.829l-2.379-2.379a12.9 12.9 0 0 0 1.582-3.814H34a2 2 0 0 0 2-2v-2A2 2 0 0 0 34 15M18 26a8 8 0 1 1 0-16a8 8 0 0 1 0 16");
}

</style>
