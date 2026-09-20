<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":28,"height":28};
const content = `<path class="lkaejxpfn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:desk-checkmark-28-regular" /></template>
<style>
.lkaejxpfn {
  fill: currentColor;
  d: path("M13.866 4a7.4 7.4 0 0 0-.594 1.5H4.753c-.69 0-1.25.56-1.25 1.25V9h9.646c.163.8.455 1.553.85 2.24L14 21.25A2.75 2.75 0 0 1 11.25 24H4.754a2.75 2.75 0 0 1-2.75-2.75V6.75A2.75 2.75 0 0 1 4.754 4zm12.135 19.25a.75.75 0 0 1-1.5 0v-9.408a7.5 7.5 0 0 0 1.5-1.246zm-22.497-2c0 .69.56 1.25 1.25 1.25h6.497c.69 0 1.25-.56 1.25-1.25L12.5 10.5H3.504zM9.75 13a.75.75 0 0 1 0 1.5h-3.5a.75.75 0 0 1 0-1.5zM20.5 1a6.5 6.5 0 1 1 0 13a6.5 6.5 0 0 1 0-13m3.854 3.646a.5.5 0 0 0-.707 0L19 9.293l-1.646-1.647a.5.5 0 1 0-.707.708l2 2a.5.5 0 0 0 .707 0l5-5a.5.5 0 0 0 0-.708");
}

</style>
