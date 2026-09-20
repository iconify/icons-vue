<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="av0fgdcla"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:calendar-checkmark-center-48-filled" /></template>
<style>
.av0fgdcla {
  fill: currentColor;
  d: path("M42 35.75A6.25 6.25 0 0 1 35.75 42h-23.5A6.25 6.25 0 0 1 6 35.75V16.5h36zm-9.362-13.134a1.25 1.25 0 0 0-1.768 0l-9.368 9.366l-4.114-4.113l-.095-.086a1.25 1.25 0 0 0-1.759 1.759l.086.095l4.998 4.999a1.25 1.25 0 0 0 1.769 0l10.25-10.252a1.25 1.25 0 0 0 0-1.768M35.75 6A6.25 6.25 0 0 1 42 12.25V14H6v-1.75A6.25 6.25 0 0 1 12.25 6z");
}

</style>
