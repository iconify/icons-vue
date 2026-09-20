<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="ny0v-x51b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:desk-checkmark-16-filled" /></template>
<style>
.ny0v-x51b {
  fill: currentColor;
  d: path("M6.602 7A5.5 5.5 0 0 0 8 8.742v2.508A1.75 1.75 0 0 1 6.25 13h-3.5A1.75 1.75 0 0 1 1 11.25V7zM15 12.5a.5.5 0 0 1-1 0V9.398a5.5 5.5 0 0 0 1-.656zm-11.5-4a.5.5 0 0 0 0 1h2a.5.5 0 0 0 0-1zm8-8.5a4.5 4.5 0 1 1 0 9a4.5 4.5 0 0 1 0-9m2.354 2.646a.5.5 0 0 0-.707 0L10.5 5.293l-.646-.647a.5.5 0 1 0-.708.708l1 1a.5.5 0 0 0 .707 0l3-3a.5.5 0 0 0 0-.708M6.208 3a5.5 5.5 0 0 0 0 3H1V4.75C1 3.784 1.784 3 2.75 3z");
}

</style>
