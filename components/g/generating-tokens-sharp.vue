<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z3lk0zbcs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:generating-tokens-sharp" /></template>
<style>
.z3lk0zbcs {
  fill: currentColor;
  d: path("M9 20q-3.35 0-5.675-2.325T1 12q0-3.35 2.325-5.675T9 4q3.35 0 5.675 2.325T17 12q0 3.35-2.325 5.675T9 20Zm-1-4.5h2v-5h2V9H6v1.5h2v5ZM19 9l-1.25-2.75L15 5l2.75-1.25L19 1l1.25 2.75L23 5l-2.75 1.25L19 9Zm0 14l-1.25-2.75L15 19l2.75-1.25L19 15l1.25 2.75L23 19l-2.75 1.25L19 23Z");
}

</style>
