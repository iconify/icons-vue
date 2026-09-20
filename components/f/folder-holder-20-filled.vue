<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="q-3ir8oux"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:folder-holder-20-filled" /></template>
<style>
.q-3ir8oux {
  fill: currentColor;
  d: path("M15.5 5A2.5 2.5 0 0 1 18 7.5v7a2.5 2.5 0 0 1-2.5 2.5H15v-4.5a1.5 1.5 0 0 0-1.5-1.5h-7A1.5 1.5 0 0 0 5 12.5V17h-.5A2.5 2.5 0 0 1 2 14.5V8h5.086a1.5 1.5 0 0 0 1.06-.44L10.707 5zm-2 7a.5.5 0 0 1 .5.5V17H6v-4.5a.5.5 0 0 1 .5-.5zm-6 2a.5.5 0 0 0 0 1h5a.5.5 0 0 0 0-1zM6.982 3c.464 0 .91.185 1.238.513l1.28 1.28l-2.06 2.06A.5.5 0 0 1 7.085 7H2V5.5A2.5 2.5 0 0 1 4.5 3z");
}

</style>
