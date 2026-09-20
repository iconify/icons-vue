<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="skjfr1kjv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:book-open-lightbulb-16-filled" /></template>
<style>
.skjfr1kjv {
  fill: currentColor;
  d: path("m14.4 13l-.239 1.196a1 1 0 0 1-.98.804h-.362a1 1 0 0 1-.98-.804L11.599 13zM6 2c.788 0 1.499.331 2 .862A2.74 2.74 0 0 1 10 2h3.25c.966 0 1.75.784 1.75 1.75v1.786a4 4 0 0 0-1.5-.505V3.75a.25.25 0 0 0-.25-.25H10c-.69 0-1.25.56-1.25 1.25v6.5c0 .69.56 1.25 1.25 1.25h.48l.3 1.5H10a2.74 2.74 0 0 1-2-.862A2.74 2.74 0 0 1 6 14H2.75A1.75 1.75 0 0 1 1 12.25v-8.5C1 2.784 1.784 2 2.75 2zM2.75 3.5a.25.25 0 0 0-.25.25v8.5c0 .138.112.25.25.25H6c.69 0 1.25-.56 1.25-1.25v-6.5c0-.69-.56-1.25-1.25-1.25zM13 6a3 3 0 0 1 1.706 5.468L14.6 12h-3.2l-.106-.532A3 3 0 0 1 13 6");
}

</style>
