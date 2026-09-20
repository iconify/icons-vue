<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="lsrxrlo8f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:document-word-48-filled" /></template>
<style>
.lsrxrlo8f {
  fill: currentColor;
  d: path("M20.75 22A3.25 3.25 0 0 1 24 25.25v15.5A3.25 3.25 0 0 1 20.75 44H5.25A3.25 3.25 0 0 1 2 40.75v-15.5A3.25 3.25 0 0 1 5.25 22zM24 15.75A4.25 4.25 0 0 0 28.25 20H40v19.75A4.25 4.25 0 0 1 35.75 44H24.872A5.23 5.23 0 0 0 26 40.75v-15.5c0-2.9-2.35-5.25-5.25-5.25H8V8.25A4.25 4.25 0 0 1 12.25 4H24zm-5.614 10.252l-1.744 9.238l-1.86-9.238h-3.644L9.36 35.24l-1.788-9.238h-2.97L7.499 40h3.639l1.864-8.4l1.78 8.4l3.604-.002L21.4 26zM26.5 4.374c.466.21.895.503 1.263.871l10.992 10.992c.368.368.662.797.871 1.263H28.25a1.75 1.75 0 0 1-1.75-1.75z");
}

</style>
