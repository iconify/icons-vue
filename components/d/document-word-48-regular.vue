<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="e_lqvcbto"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:document-word-48-regular" /></template>
<style>
.e_lqvcbto {
  fill: currentColor;
  d: path("M20.75 22A3.25 3.25 0 0 1 24 25.25v15.5A3.25 3.25 0 0 1 20.75 44H5.25A3.25 3.25 0 0 1 2 40.75v-15.5A3.25 3.25 0 0 1 5.25 22zm4.008-18a4.25 4.25 0 0 1 3.005 1.245l10.992 10.992A4.25 4.25 0 0 1 40 19.242V39.75A4.25 4.25 0 0 1 35.75 44H24.872a5.2 5.2 0 0 0 1.073-2.5h9.805a1.75 1.75 0 0 0 1.75-1.75V20h-9.25A4.25 4.25 0 0 1 24 15.75V6.5H12.25a1.75 1.75 0 0 0-1.75 1.75V20H8V8.25A4.25 4.25 0 0 1 12.25 4zm-6.372 22.002l-1.744 9.238l-1.86-9.238h-3.644L9.36 35.24l-1.788-9.238h-2.97L7.499 40h3.639l1.864-8.4l1.78 8.4l3.604-.002L21.4 26zM26.5 15.75c0 .966.784 1.75 1.75 1.75h8.232L26.5 7.518z");
}

</style>
