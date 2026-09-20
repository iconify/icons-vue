<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="c9v4nfsge"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:fluent-20-regular" /></template>
<style>
.c9v4nfsge {
  fill: currentColor;
  d: path("M10.276 2.053a.5.5 0 0 1 .448 0l5 2.5a.5.5 0 0 1 0 .894L11.618 7.5l4.106 2.053a.5.5 0 0 1 0 .894L11 12.81v4.69a.5.5 0 0 1-.757.429l-5-3A.5.5 0 0 1 5 14.5V5a.5.5 0 0 1 .276-.447zM6 5.309v8.908l4 2.4v-3.808a1 1 0 0 1 .553-.894L14.382 10l-4.106-2.053a.5.5 0 0 1 0-.894L14.382 5L10.5 3.059z");
}

</style>
