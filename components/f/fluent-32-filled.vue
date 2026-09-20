<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="v-41pwb8a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:fluent-32-filled" /></template>
<style>
.v-41pwb8a {
  fill: currentColor;
  d: path("M17.447 2.106a1 1 0 0 0-.894 0l-8 4A1 1 0 0 0 8 7v17.5a1 1 0 0 0 .51.872l8 4.5A1 1 0 0 0 18 29v-9.382l7.447-3.724a1 1 0 0 0 0-1.788L19.237 11l6.21-3.106a1 1 0 0 0 0-1.788z");
}

</style>
