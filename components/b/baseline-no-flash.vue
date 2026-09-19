<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ftybpib_b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:baseline-no-flash" /></template>
<style>
.ftybpib_b {
  fill: currentColor;
  d: path("M13.93 13.93L2.45 2.45L1.04 3.87l5.3 5.3l-.2.23H3.6c-.88 0-1.6.72-1.6 1.6v9.4c0 .88.72 1.6 1.6 1.6h12.8c.75 0 1.38-.52 1.55-1.22l2.18 2.18l1.41-1.41L18 18zM10 20c-2.21 0-4-1.79-4-4c0-1.95 1.4-3.57 3.25-3.92l1.57 1.57c-.26-.09-.53-.15-.82-.15a2.5 2.5 0 0 0 0 5a2.5 2.5 0 0 0 2.5-2.5c0-.29-.06-.56-.15-.82l1.57 1.57A3.99 3.99 0 0 1 10 20m8-4.83L10.83 8h1.75l1.28 1.4h2.54c.88 0 1.6.72 1.6 1.6zm2.4-9.57H22L19 11V7h-1V2h4z");
}

</style>
