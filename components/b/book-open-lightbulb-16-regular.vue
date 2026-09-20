<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="hfsuelbfx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:book-open-lightbulb-16-regular" /></template>
<style>
.hfsuelbfx {
  fill: currentColor;
  d: path("m14.4 13l-.239 1.196a1 1 0 0 1-.98.804h-.362a1 1 0 0 1-.98-.804L11.599 13zM6 2c.818 0 1.544.393 2 1c.456-.607 1.182-1 2-1h3.5A1.5 1.5 0 0 1 15 3.5v2.036a4 4 0 0 0-1-.41V3.5a.5.5 0 0 0-.5-.5H10a1.5 1.5 0 0 0-1.5 1.5v7A1.5 1.5 0 0 0 10 13h.58l.2 1H10a2.5 2.5 0 0 1-2-1c-.456.607-1.182 1-2 1H2.5A1.5 1.5 0 0 1 1 12.5v-9A1.5 1.5 0 0 1 2.5 2zM2.5 3a.5.5 0 0 0-.5.5v9a.5.5 0 0 0 .5.5H6a1.5 1.5 0 0 0 1.5-1.5v-7A1.5 1.5 0 0 0 6 3zM13 6a3 3 0 0 1 1.706 5.468L14.6 12h-3.2l-.106-.532A3 3 0 0 1 13 6");
}

</style>
