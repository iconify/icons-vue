<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":28,"height":28};
const content = `<path class="u0evnfxnv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:desk-multiple-checkmark-28-regular" /></template>
<style>
.u0evnfxnv {
  fill: currentColor;
  d: path("M13.068 6.5q-.066.49-.068 1q.001.252.019.5H4.75c-.69 0-1.25.56-1.25 1.25v2.25h10.657c.35.553.768 1.057 1.245 1.5H13v8.25A2.75 2.75 0 0 1 10.25 24h-5.5A2.75 2.75 0 0 1 2 21.25v-12A2.75 2.75 0 0 1 4.75 6.5zM23.5 23.25a.75.75 0 0 1-1.5 0v-8.4a7.4 7.4 0 0 0 1.5-.477zm-20-2c0 .69.56 1.25 1.25 1.25h5.5c.69 0 1.25-.56 1.25-1.25V13h-8zm22.502-.5a.75.75 0 0 1-1.5 0v-6.91a7.5 7.5 0 0 0 1.5-1.245zM9.25 15a.75.75 0 0 1 0 1.5h-3.5a.75.75 0 0 1 0-1.5zM20.5 1a6.5 6.5 0 1 1 0 13a6.5 6.5 0 0 1 0-13m3.854 3.646a.5.5 0 0 0-.707 0L19 9.293l-1.646-1.647a.5.5 0 1 0-.707.708l2 2a.5.5 0 0 0 .707 0l5-5a.5.5 0 0 0 0-.708M13.866 4a7.4 7.4 0 0 0-.594 1.5H4.804A2.75 2.75 0 0 1 7.252 4z");
}

</style>
