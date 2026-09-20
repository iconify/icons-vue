<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":28,"height":28};
const content = `<path class="z7lekdgmp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:data-bar-vertical-28-regular" /></template>
<style>
.z7lekdgmp {
  fill: currentColor;
  d: path("M6 3a3 3 0 0 1 3 3v16a3 3 0 1 1-6 0V6a3 3 0 0 1 3-3m8 5a3 3 0 0 1 3 3v11a3 3 0 1 1-6 0V11a3 3 0 0 1 3-3m8 5a3 3 0 0 1 3 3v6a3 3 0 1 1-6 0v-6a3 3 0 0 1 3-3M6 4.5A1.5 1.5 0 0 0 4.5 6v16a1.5 1.5 0 0 0 3 0V6A1.5 1.5 0 0 0 6 4.5m8 5a1.5 1.5 0 0 0-1.5 1.5v11a1.5 1.5 0 0 0 3 0V11A1.5 1.5 0 0 0 14 9.5m8 5a1.5 1.5 0 0 0-1.5 1.5v6a1.5 1.5 0 0 0 3 0v-6a1.5 1.5 0 0 0-1.5-1.5");
}

</style>
