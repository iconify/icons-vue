<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ga2q-ygvx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:app-generic-32-light" /></template>
<style>
.ga2q-ygvx {
  fill: currentColor;
  d: path("M24.5 29a4.5 4.5 0 0 0 4.5-4.5v-17A4.5 4.5 0 0 0 24.5 3h-17A4.5 4.5 0 0 0 3 7.5v17A4.5 4.5 0 0 0 7.5 29zM4 7.5A3.5 3.5 0 0 1 7.5 4h17A3.5 3.5 0 0 1 28 7.5V10H4zm0 17V11h24v13.5a3.5 3.5 0 0 1-3.5 3.5h-17A3.5 3.5 0 0 1 4 24.5M9 14a2 2 0 0 0-2 2v7a2 2 0 0 0 2 2h3a2 2 0 0 0 2-2v-7a2 2 0 0 0-2-2zm-1 2a1 1 0 0 1 1-1h3a1 1 0 0 1 1 1v7a1 1 0 0 1-1 1H9a1 1 0 0 1-1-1zm8-.5a.5.5 0 0 1 .5-.5h8a.5.5 0 0 1 0 1h-8a.5.5 0 0 1-.5-.5m.5 3.5a.5.5 0 0 0 0 1h6a.5.5 0 0 0 0-1z");
}

</style>
