<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cgt666bpl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:highlight-24-filled" /></template>
<style>
.cgt666bpl {
  fill: currentColor;
  d: path("M5.25 2A2.25 2.25 0 0 0 3 4.25v3A2.25 2.25 0 0 0 5.25 9.5h13.5A2.25 2.25 0 0 0 21 7.25v-3A2.25 2.25 0 0 0 18.75 2zM5 11.75V11h14v.75A2.25 2.25 0 0 1 16.75 14h-9.5A2.25 2.25 0 0 1 5 11.75m2.503 3.75H16.5v1.288a2.25 2.25 0 0 1-1.141 1.958l-.154.08l-6.635 3.106a.75.75 0 0 1-1.061-.578l-.007-.101z");
}

</style>
