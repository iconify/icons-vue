<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k4nujbcjv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:factory-outline-rounded" /></template>
<style>
.k4nujbcjv {
  fill: currentColor;
  d: path("M4 22q-.825 0-1.412-.587T2 20v-8.7q0-.6.325-1.1t.9-.75L7.6 7.6q.5-.2.95.075T9 8.5V9l3.625-1.45q.5-.2.937.1t.438.825V10h8v10q0 .825-.587 1.413T20 22zm0-2h16v-8h-8V9.95l-5 2V10l-3 1.325zm7-2h2v-4h-2zm-4 0h2v-4H7zm8 0h2v-4h-2zm7-8h-5l.9-7.125q.05-.375.325-.625t.65-.25h1.25q.375 0 .65.25t.325.625zM4 20h16z");
}

</style>
