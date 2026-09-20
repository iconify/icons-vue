<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="v5o79uvnj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:chat-checkmark-48-regular" /></template>
<style>
.v5o79uvnj {
  fill: currentColor;
  d: path("M24 4c11.046 0 20 8.954 20 20s-8.954 20-20 20c-3.45 0-6.698-.874-9.533-2.414L6.23 43.928c-1.318.374-2.536-.844-2.16-2.162l2.341-8.238A19.9 19.9 0 0 1 4 24C4 12.954 12.954 4 24 4m0 2.5C14.335 6.5 6.5 14.335 6.5 24c0 3.188.851 6.173 2.338 8.745c.17.293.213.642.12.968l-2.116 7.442l7.44-2.116a1.25 1.25 0 0 1 .968.12A17.4 17.4 0 0 0 24 41.5c9.665 0 17.5-7.835 17.5-17.5S33.665 6.5 24 6.5m6.865 11.12a1.25 1.25 0 0 1 1.768 1.767L21.637 30.383a1.25 1.25 0 0 1-1.768 0l-4.503-4.5a1.25 1.25 0 0 1 1.768-1.768l3.618 3.616z");
}

</style>
