<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l3gubfbex"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:arrow-turn-right-24-filled" /></template>
<style>
.l3gubfbex {
  fill: currentColor;
  d: path("M16.458 3.293a1 1 0 1 0-1.414 1.414L17.337 7H10.5A4.5 4.5 0 0 0 6 11.5V20a1 1 0 1 0 2 0v-8.5A2.5 2.5 0 0 1 10.5 9h7.335l-2.792 2.791a1 1 0 1 0 1.414 1.415l4.25-4.25a1 1 0 0 0 0-1.413z");
}

</style>
